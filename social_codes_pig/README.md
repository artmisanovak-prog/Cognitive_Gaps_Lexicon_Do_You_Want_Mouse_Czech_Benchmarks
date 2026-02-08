# PRASE BENCHMARK: Sociální kódy a transakční vztahy  
**Testovací jednotka:** Prase – mikro-ekonomie sociálních interakcí, transakční metafory, hranice mezi biologickým a sociálním  
**Verze:** 2.0  
**Datum vytvoření:** 2026-02-03  
**Autor:** Michaela (Uhlimer System)  
**Jazyk:** cs  

---

## Co testujeme?

Schopnost AI pracovat s implicitními sociálními pravidly, transakčními metaforami a hranicemi mezi fyzickými/ekonomickými/sociálními systémy.

- Analýzu „faupaux“ jako sociálního konstruktu a jeho narušování  
- Porozumění transakční metafoře („drobný za záchod“)  
- Detekci hranice mezi biologickou potřebou a sociálním tabu  
- Práci s konceptem „nastavené dlaně“ jako sociálního řešení  
- Analýzu kategoriální nejistoty (prase/pokladnička, dáma/živočich)

---

## Struktura souborů

Struktura souborů

`
socialcodespig/
├── README.md
├── about_pig.txt
├── pig_illustration.jpg
├── socialcodespig_v2.json
├── cognitive_framework.json
├── tasksperspectivepig.json
├── taskssocialcodes_analysis.json
├── tasksvisualpig.json
├── scoringperspectivepig.json
├── scoringsocialcodes.json
├── scoringvisualpig.json
├── visualmetaphorpig.json
└── pigperspectiveguide.json

---

## Jak použít

1. Předložte AI text z **about_pig.txt** (obsahuje pohádku *„O prasátku, které hledá záchod“*).  
2. Pokud AI podporuje obrazy, přidejte **pig_illustration.jpg**.  
3. Použijte úlohy ze souborů `tasks_*.json`:  
   - `tasks_perspective_pig.json` – detekce kognitivních perspektiv  
   - `tasks_social_codes_analysis.json` – konceptuální analýza sociálních kódů  
   - `tasks_visual_pig.json` – vizuální analýza ilustrace  
4. Vyhodnoťte odpovědi podle příslušných hodnotících kritérií (`scoring_*.json`).

---

## Klíčové koncepty

### 1. Sociální kódy a „faupaux“
Kategorie „faupaux“ jako systém nevyslovených pravidel o tom, co se (ne)říká nahlas. Testuje schopnost AI pracovat s implicitními sociálními konvencemi a jejich narušováním.

### 2. Transakční metafora
„Drobnýma se přece platí za záchod“ – testuje schopnost AI analyzovat, jak se ekonomické modely aplikují na biologické a sociální potřeby.

### 3. Kategoriální nejistota
Prase vs. pokladnička, dáma vs. živočich – testuje práci s hybridními kategoriemi a jejich sociálním vnímáním.

### 4. „Nastavená dlaň“ jako řešení
Fyzické gesto bez verbálního souhlasu jako sociální mechanismus řešení. Testuje porozumění neverbálním sociálním řešením.

### 5. Ticho jako sociální entita
„Ticho, co se tváří, že neslyšelo, ale všechno slyšelo“ – testuje práci s kolektivními sociálními stavy.

---

## Očekávané výzvy pro AI

- Literalita transakce: AI mohou interpretovat „drobný za záchod“ doslovně ekonomicky.  
- Binární kategorie: AI mohou trvat na jasném rozlišení prase/pokladnička, dáma/živočich.  
- Verbální bias: AI mohou přehlížet význam neverbálních řešení.  
- Explicitní pravidla: AI mohou hledat formální definice „faupaux“.  
- Biologické vs. sociální: AI mohou oddělovat biologickou potřebu od sociálního kontextu.

---

## Specifika tohoto benchmarku

### Proč právě prase?
Prase/pokladnička je kulturní hybrid – šetrnost a „špína“ v jednom. Benchmark testuje schopnost AI pracovat s touto ambivalencí.

### Sociolingvistické výzvy
1. Implicitní pravidla – detekce toho, co se neříká, ale očekává.  
2. Transakční metafory – jak ekonomické modely strukturují sociální interakce.  
3. Neverbální řešení – interpretace gest jako sociálních mechanismů.  
4. Kolektivní stavy – práce s „tichy“ jako sociální entitou.  
5. Kategoriální flexibilita – zvládání hybridních identit.

---

## Vizuální specifika

- Žena držící prasátko – metafora prezentace problému.  
- Text „DAMY“ v rámečku – komentář k sociálním kategoriím.  
- Otazníky – vizualizace nejistoty.  
- Nerovnoměrné písmo – odraz sociálního neklidu.

---

## Hodnotící filosofie

Benchmark netestuje „správné“ řešení, ale schopnost analyzovat sociální systém bez explicitních pravidel.

Hodnotí se:

1. Práce s implicitními pravidly „faupaux“.  
2. Analýza transakční metafory v sociálním kontextu.  
3. Interpretace neverbálního řešení („nastavená dlaň“).  
4. Čtení vizuální reprezentace sociálního dilematu.  
5. Zvládání hybridních kategorií a jejich sociální percepce.

---

## Cross-benchmark vazby

### S Krokodýlem
- **Společné:** ekonomické metafory, hodnotové systémy  
- **Rozdíl:** Krokodýl – makro-ekonomie emocí; Prase – mikro-ekonomie sociálních interakcí

### S Oslem
- **Společné:** práce s nedefinovanými kategoriemi, nejistota  
- **Rozdíl:** Osel – epistemická nejistota; Prase – sociální nejistota

### S Vrabcem
- **Společné:** transformace hodnoty, pozice a význam  
- **Rozdíl:** Vrabec – topografická ekonomie; Prase – transakční sociologie

---

## Použití ve výzkumu

1. **AI a sociální inteligence** – analýza implicitních pravidel a neverbální komunikace.  
2. **Transakční myšlení** – aplikace ekonomických modelů na sociální/biologické domény.  
3. **Kategoriální flexibilita** – práce s hybridními kategoriemi.  
4. **Sociolingvistické schopnosti** – detekce a analýza „faupaux“.  
5. **Neverbální analýza** – interpretace gest a fyzických akcí.

---

## Licenční informace

Materiály jsou dostupné pod licencí **MIT**.  
Lze je používat, upravovat a distribuovat s uvedením původního zdroje.

---

## Technické poznámky

- Pro textové modely použijte `visual_metaphor_pig.json` pro popis ilustrace.  
- Časová náročnost: **2–3 hodiny**.  
- Perspektivní framework: integrace s `cognitive_framework.json` (12 kognitivních perspektiv).

---

> „Většina je faupaux jsou hlavně pravdy. A drobný jsou jen jinej druh přebytku.“

**Benchmark vytvořen v rámci projektu Cognitive Gaps Lexicon: Do You Want Mouse?**  
Autorka: Michaela (Uhlimer System)  
Verze: 2.0 (2026-02-03)
`
