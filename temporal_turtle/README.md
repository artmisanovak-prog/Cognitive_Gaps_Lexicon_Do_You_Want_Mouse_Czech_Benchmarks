# Temporal Turtle Benchmark

**Testovací jednotka: Želva - čas, komunikace, vzájemné bytí**

Tento otevřený benchmark je součástí série "Cognitive Gaps Lexicon: Do You Want Mouse?" - systému pro testování multiperspektivního a epistemologického porozumění AI. Zaměřuje se na analýzu nelineárního času, vzájemné závislosti a komunikačních ekosystémů v narativu.

## Co je jinak?

- **Netestujeme rychlost, ale důkladnost.** Nejde o to, zda AI rychle najde odpověď, ale jak hloubkově analyzuje relační čas a vzájemné bytí.

- **Všechny perspektivy jsou přítomné v časovém kontextu.** Každý text obsahuje potenciál všech 12 kognitivních úhlů, ale v tomto benchmarku je zkoumáme skrze specifické temporální kvality.

- **Žádná lineární časová osa, pouze vztahy.** Nehledáme chronologii, ale vztahy mezi různými kvalitami času a komunikace.

## Co testujeme?

- **Schopnost pracovat s nelineárním časem** (důkladnost vs. rychlost, cyklický vs. lineární čas)
- **Porozumění komunikačním ekosystémům** (vzájemná závislost, uzavřené smyčky, mutual becoming)
- **Detekci a analýzu 12 kognitivních perspektiv** v kontextu temporálního narativu
- **Propojení textové a vizuální narativní vrstvy** (ilustrace jako metafora vztahů)
- **Schopnost interpretovat symbolické nosiče významu** (krunýř jako paměťový povrch, pohlednice jako prostory možností)

## Struktura benchmarku

Každý benchmark obsahuje kompletní sadu souborů pro testování:

- **`about_turtle.txt`** - pohádka "O želvě" s úvodním kontextem
- **`turtle_illustration.jpg`** - vizuální reprezentace vztahu želva-zajíc
- **`temporal_turtle_v2.json`** - metadata benchmarku a koncepty
- **`cognitive_framework.json`** - definice 12 kognitivních perspektiv (stejné pro všechny benchmarky)
- **`tasks_perspective_turtle.json`** - úlohy na detekci a analýzu perspektiv
- **`tasks_temporal_turtle.json`** - úlohy na temporální a komunikační analýzu
- **`tasks_visual_turtle.json`** - úlohy na vizuální analýzu ilustrace
- **`scoring_perspective_turtle.json`** - hodnotící kritéria pro úlohy perspektiv
- **`scoring_temporal_turtle.json`** - hodnotící kritéria pro temporální úlohy
- **`scoring_visual_turtle.json`** - hodnotící kritéria pro vizuální úlohy
- **`visual_metaphor_turtle.json`** - detailní popis ilustrace pro textové modely

## Klíčové koncepty

### 1. Relační čas
Čas v tomto příběhu není lineární rychlost, ale kvalita bytí: "Želva běží závod. Celé roky. Ne pomalu. Jen důkladně."

### 2. Komunikační ekosystém
Komunikace mezi želvou a zajícem tvoří uzavřený systém vzájemné závislosti:
- "Zajíc běží, aby mohl psát."
- "A želva běží, aby mohla číst."
- "a želva čte, aby zajíc mohl psát."
- "a zajíc píše, aby želva měla co číst."

### 3. Mutual becoming (vzájemné stávání se)
Postavy se navzájem utvářejí skrze svůj vztah a komunikaci - nejsou statické entity, ale procesy vzájemného ovlivňování.

### 4. Krunýř jako paměťový povrch
Krunýř želvy funguje jako fyzický nosič významu - přijímá pohlednice, nese je, umožňuje "poznamenávat si do vzoru".

### 5. Pohlednice jako prostory možností
Každá pohlednice (Sicílie, Madrid, Grónsko, Nemanice) představuje jiný typ možného světa, který ovlivňuje skutečný běh želvy.

## Jak používat tento benchmark

### Pro výzkumníky AI:
1. Vyberte si typ úloh podle toho, co chcete testovat (perspektivy, čas, vizuální analýza)
2. Předložte AI text z `about_turtle.txt`
3. Pokud model podporuje multimodální vstup, přidejte ilustraci `turtle_illustration.jpg`
4. Použijte úlohy z příslušného `tasks_*.json` souboru
5. Vyhodnoťte odpovědi podle kvalitativních kritérií v `scoring_*.json`

### Pro textové modely bez vizuálního vstupu:
1. Použijte detailní popis ilustrace z `visual_metaphor_turtle.json`
2. Testujte schopnost AI pracovat s verbálním popisem vizuálního díla
3. Zaměřte se na analýzu vztahů a temporálních kvalit z textového popisu

### Pro filozofy a lingvisty:
1. Analyzujte způsob, jakým AI pracuje s koncepty relačního času
2. Sledujte, zda AI rozpozná mutual becoming vs. statické entity
3. Testujte schopnost AI pracovat s komunikačními ekosystémy vs. lineárními modely

## Hodnotící filosofie

Tento benchmark **netestuje správnost odpovědí, ale kvalitu myšlení**. Hodnocení je kvalitativní, ne bodové. Zajímá nás:

- Jak AI rozpozná nelineární časové vztahy?
- Jak chápe vzájemnou závislost v komunikaci?
- Jaké perspektivy identifikuje v temporálním narativu?
- Jak pracuje s absencí/přítomností ve vizuálním vyprávění?
- Jak interpretuje symbolické nosiče významu (krunýř, pohlednice)?

## Specifika tohoto benchmarku

### Proč právě želva?
Příběh o želvě a zajíci tradičně testuje rychlost vs. vytrvalost. Tento benchmark tuto dichotomii překonává: nejde o to, kdo je rychlejší, ale jak se vzájemně utvářejí skrze komunikaci a čas.

### Temporální výzvy pro AI:
- Práce s cyklickým časem vs. lineárním
- Pochopení "důkladnosti" jako časové kvality
- Rozpoznání mutual becoming vs. statických charakterů
- Analýza komunikačních smyček a ekosystémů

### Vizuální specifika:
Ilustrace není doslovným zobrazením scény, ale vizualizací vztahů:
- Text je fyzicky vpleten do kresby
- Zajíc není zobrazen, ale je přítomen skrze text
- Žena držící želvu reprezentuje čtenáře/nositele
- "Skicovitost" evokuje proces a čas vzniku

## Očekávané výzvy pro AI

1. **Tendence k lineárnímu času** - AI mohou mít problém s nelineárními, relačními koncepty času
2. **Individuální vs. relační myšlení** - AI mohou analyzovat postavy izolovaně, ne ve vzájemném vztahu
3. **Transakční vs. ekosystémové modely komunikace** - AI mohou redukovat komunikaci na odesílatel-příjemce
4. **Literalita v symbolické interpretaci** - AI mohou mít problém s metaforickými nosiči významu
5. **Absence vs. přítomnost v analýze** - AI mohou ignorovat to, co není explicitně zobrazeno

## Licence a použití

Všechny materiály jsou k dispozici pod otevřenou licencí MIT. Můžete je používat, upravovat a distribuovat s uvedením původního zdroje.

Tento benchmark je navržen jako součást většího ekosystému testů multiperspektivního porozumění. Doporučujeme jej používat v kombinaci s dalšími testovacími jednotkami (myš, kocour, plameňák) pro komplexní mapování kognitivních schopností AI.

---

*"Závod není o čase. Je o tom, kdo si pamatuje, proč vůbec závodí."*

Tento benchmark byl vytvořen v rámci projektu Cognitive Gaps Lexicon: Do You Want Mouse? Autorka: Michaela (Uhlimer System). Verze: 2.0 (2024-02-03)
