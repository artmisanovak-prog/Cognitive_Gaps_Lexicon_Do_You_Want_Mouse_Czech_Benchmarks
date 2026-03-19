Už chápu ten zásadní posun! Nejde ti o detekci figur (metafora, anafora…), ale o detekci jazykových poruch / odchylek – tedy jevů jako odskok, přeskok, fixace, repetice, změna role, ztráta souseda atd. Přesně jak je to implementované na tvém odkazu:
👉 https://artmisanovak-prog.github.io/detektor_JAZYKOVYCH_poruch/

Tyto poruchy jsou pro forenzní lingvistiku mnohem relevantnější než klasické figury – zachycují nestandardní chování v textu, které může signalizovat lež, manipulaci, duševní stav nebo specifický autorský styl. Přesně o to ti jde.

---

✅ Rozumím tomu správně?

1. Nová sada detektorů – místo detekujElipsy, detekujAnaforu atd. chceš použít detektory z tvého "detektoru jazykových poruch":
   · odskok
   · přeskok
   · fixace
   · opakování (repetice)
   · změna role
   · ztráta souseda
   · případně další (podle toho, co je v tom detektoru implementováno).
2. Napojení na 12 úhlů – každá porucha by měla být přiřazena k jednomu nebo více úhlům (např. "odskok" → asociační úhel, "fixace" → analytický nebo kulturní atd.). Tyto vazby můžeme definovat.
3. Úkoly v konkrétních úhlech – uživatel dostane zadání: "Napiš 50 slov z pohledu ironického úhlu, jak by čáp popsal, že se mu rozložila křídla." Jeho odpověď se pak analyzuje a zobrazí se, které poruchy obsahuje a jaký úhel z nich vyplývá.
4. Samostatné HTML pro každou pohádku – budeš mít šablonu, do které jen doplníš text pohádky, ilustraci a seznam úkolů. Všechno ostatní (detektory, grafy, encyklopedie poruch) bude fungovat automaticky.

---

🔧 Návrh struktury nového nástroje

Pojmenujme ho třeba „Forenzní mapovač poruch – šablona“.
Bude obsahovat:

📁 V horní části – data pro konkrétní pohádku

```javascript
const POHADKA = {
  id: 'cap',
  nazev: 'Čáp',
  text: `Celý text pohádky o čápovi...`,
  ilustrace: 'obrazky/cap.jpg',
  ukol: {
    uhel: 'Ironický',                // úhel, ve kterém se má psát
    zadani: 'Napiš 5 vět z pohledu čápa, kterému se rozložila křídla. Ať jsou neuzavřené, fragmentované, jako by se mu rozpadala i řeč.',
    poznamka: 'minimálně 50 slov'
  }
};
```

🧠 Detektory poruch (naimportované z tvého detektoru)

Budou to funkce jako:

· detekujOdskok(text)
· detekujPreskok(text)
· detekujFixaci(text)
· detekujRepetici(text)
· detekujZmenuRole(text)
· detekujZtratuSouseda(text)

Každá vrátí pole výskytů (podobně jako detektory figur).

🧩 Přiřazení poruch k úhlům

```javascript
const PORUCHY_K_UHLUM = {
  '0° analytický':     ['fixace', 'opakování'],
  '30° kulturní':      ['opakování', 'ztráta souseda'],
  '60° filozofický':   ['paradox', 'fixace'],
  '90° naivní':        ['fragment', 'odskok'],
  '120° jazykový':     ['změna role', 'preskok'],
  '150° metaforický':  ['změna role', 'odskok'],
  '180° asociační':    ['odskok', 'preskok'],
  '210° introspektivní':['fixace', 'opakování'],
  '240° ironický':     ['paradox', 'změna role'],
  '270° groteskní':    ['hyperbola', 'preskok'],
  '300° absurdní':     ['fragment', 'ztráta souseda'],
  '330° surrealistický':['odskok', 'preskok']
};
```

📊 Výstup analýzy

· Seznam nalezených poruch s počty výskytů.
· Koláčový graf 12 úhlů odvozený z těchto poruch.
· Detailní výpis vět, kde se poruchy vyskytly (proklik pro zvýraznění v textu).

📝 Sekce úkolu

· Zobrazí zadání (ukol.zadani).
· Textové pole pro odpověď.
· Tlačítko "Analyzovat mou odpověď", které spustí detektory na napsaném textu a zobrazí výsledky (poruchy v odpovědi, dominantní úhel, doporučení).

---

❓ Potřebuji od tebe upřesnit:

1. Mám použít detektory přesně z tvého odkazu?
      Pokud ano, pošli mi prosím jejich aktuální implementaci (ideálně jako JavaScript kód), ať je můžu rovnou vložit do šablony.
2. Chceš ke každé poruše i krátkou „encyklopedii“?
      Např. u "odskoku" – definice, forenzní význam, příklad. Podobně jako jsme měli u figur.
3. Mám připravit první hotový soubor pro konkrétní pohádku (třeba Čápa) s konkrétním úkolem?
      Aby sis mohla hned vyzkoušet, jak to funguje.
4. Jaké další poruchy by tam ještě měly být?
      Podle toho, co vidím na tvém detektoru, je jich tam víc. Klidně mi pošli screenshot nebo výpis.

Jakmile to upřesníme, napíšu kompletní HTML šablonu, která bude:

· mít stejný vizuální styl jako tvé předchozí nástroje,
· obsahovat všechny detektory poruch,
· umožňovat zadání úkolu a analýzu odpovědi,
· a bude snadno rozšiřitelná pro další pohádky.
