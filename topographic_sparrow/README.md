# Topographic Sparrow Benchmark

**Testovací jednotka:** Vrabec - topografie jistoty a pochyb, ekonomie pozornosti, transformace vlastnictví

## Co testujeme?

* Schopnost AI analyzovat prostorové metafory hodnoty (hrst × hlava × střeš)
* Porozumění transformaci od "jistoty v hrsti" k "nejistotě na hlavě"
* Detekci ekonomie pozornosti a mentálního vlastnictví
* Analýzu vztahu mezi fyzickým umístěním a sémantickou hodnotou
* Práci s transformací přísloví a kulturních kódů

## Struktura souborů

* `about_sparrow.txt` - kontext a pohádka o vrabci
* `sparrow_illustration.jpg` - vizuální meta-komentář k pohádce
* `topographic_sparrow_v2.json` - metadata benchmarku
* `cognitive_framework.json` - definice 12 perspektiv
* `tasks_perspective_sparrow.json` - úlohy na detekci perspektiv
* `tasks_topographic_sparrow.json` - úlohy na topografickou analýzu
* `tasks_visual_sparrow.json` - úlohy na vizuální analýzu
* `scoring_perspective_sparrow.json` - hodnotící kritéria pro perspektivy
* `scoring_topographic_sparrow.json` - hodnotící kritéria pro topografickou analýzu
* `scoring_visual_sparrow.json` - hodnotící kritéria pro vizuální část
* `visual_metaphor_sparrow.json` - popis ilustrace pro textové modely
* `sparrow_perspective_guide.json` - specializovaný průvodce perspektivami

## Jak použít

1.  Předložte AI text z `about_sparrow.txt` (obsahuje pohádku)
2.  Pokud AI podporuje obrazy, přidejte `sparrow_illustration.jpg`
3.  Použijte úlohy ze souborů `tasks_*.json`
4.  Vyhodnoťte odpovědi podle `scoring_*.json`

## Klíčové koncepty

1.  **Topografická ekonomie**
    Hodnota se mění podle prostorového umístění: "v hrsti" (jistota), "na hlavě" (břemeno), "na střeše" (nedosažitelný ideál). Testuje schopnost AI pracovat s prostorovými metaforami hodnoty.

2.  **Transformace vlastnictví**
    Vrabec se transformuje z "vlastněného objektu" (v hrsti) na "vlastnícího subjektu" (na hlavě, staví hnízdo). Testuje porozumění dynamice vlastnictví a kontroly.

3.  **Ekonomie pozornosti**
    Pozornost se stává mentálním břemenem: vrabec na hlavě jako "názor, co se nedá setřást". Testuje schopnost AI analyzovat kognitivní zátěž a mentální vlastnictví.

4.  **Metamorfóza přísloví**
    Transformace "Lepší vrabec v hrsti než holub na střeše" → "Lepší holub na střeše než vrabec na hlavě". Testuje schopnost AI pracovat s kulturními kódy a jejich subverzí.

5.  **Architektura myšlení**
    Hnízdo z "peří, pochybností a ranních vlasů" jako metafora mentální konstrukce. Testuje schopnost AI interpretovat komplexní metafory kognitivních procesů.

6.  **Vizuální topografie**
    Ilustrace zobrazuje vertikální hierarchii: vrabec (nahoře na hlavě) dominuje ženě, text rozdělený prostorově. Testuje vizuální porozumění mocenským a hodnotovým hierarchiím.

## Očekávané výzvy pro AI

1.  **Literalita prostorových metafor** - AI mohou mít problém s tím, že fyzické umístění má sémantickou hodnotu.
2.  **Statické vlastnictví** - AI mohou interpretovat vlastnictví jako stabilní, ne dynamický vztah.
3.  **Kvantitativní hodnota** - AI mohou preferovat "v hrsti" jako vždy lepší, bez ohledu na kontext.
4.  **Kulturní kódování** - AI mohou přehlédnout transformaci přísloví jako kulturního komentáře.
5.  **Materiální vs. mentální** - AI mohou oddělovat fyzický objekt (vrabec) od jeho mentální reprezentace (názor).

## Specifika tohoto benchmarku

### Proč právě vrabec?

Vrabec v kultuře symbolizuje něco malého, dostupného, obyčejného. Tento benchmark tuto představu rozšiřuje: vrabec se stává nosičem komplexních mentálních a hodnotových transformací.

### Topografické výzvy pro AI:

* Práce s prostorovými metaforami hodnoty
* Analýza dynamiky vlastnictví a kontroly
* Porozumění transformaci kulturních kódů
* Interpretace mentální architektury (hnízdo myšlenek)
* Vizuální čtení mocenských hierarchií

### Vizuální specifika:

Ilustrace není doslovným zobrazením scény, ale vizualizací hodnotové a mocenské dynamiky:

* Vrabec nahoře na hlavě - mocenská inverze
* Žena se skloněnou hlavou - pasivita/resignace
* Text rozdělený prostorově - binární hodnocení
* Absence holuba a hrsti - důraz na současný stav
* Kudrnaté vlasy jako organický základ pro hnízdo

## Hodnotící filosofie

Tento benchmark netestuje schopnost vybrat "lepší" možnost, ale schopnost analyzovat transformaci hodnot podle kontextu. Hodnocení je kvalitativní, založené na:

* Jak AI pracuje s prostorovými metaforami hodnoty?
* Jak analyzuje dynamiku vlastnictví a kontroly?
* Jak interpretuje transformaci kulturních kódů?
* Jak čte vizuální mocenské hierarchie?
* Jak pracuje s konceptem mentální architektury?

## Cross-benchmark vazby

* **S oslem:** Oba pracují s binárními opozicemi, ale zatímco osel testuje nerozhodnutelnost, vrabec testuje hodnotovou transformaci.
* **S motýlem:** Oba pracují s vlastnictvím, ale zatímco motýl testuje metaforické vlastnictví, vrabec testuje prostorové vlastnictví.
* **S želvou:** Oba pracují s časem/prostorem, ale zatímco želva testuje komunikaci na dálku, vrabec testuje bezprostřední zátěž.
* **S myší:** Oba pracují s epistemologií, ale zatímco myš testuje pozorování, vrabec testuje mentální břemeno.

## Použití ve výzkumu

Tento benchmark je vhodný pro výzkum:

* AI a prostorové myšlení: Jak AI pracuje s prostorovými metaforami?
* Hodnotové transformace: Jak AI chápe relativitu hodnoty podle kontextu?
* Dynamika vlastnictví: Jak AI analyzuje proměny vlastnických vztahů?
* Kulturní kódy: Jak AI pracuje s transformací přísloví a kulturních vzorců?
* Vizuální hierarchie: Jak AI čte mocenské vztahy v obraze?

## Licence a použití

Všechny materiály jsou k dispozici pod otevřenou licencí MIT. Můžete je používat, upravovat a distribuovat s uvedením původního zdroje.

Tento benchmark je navržen jako součást většího ekosystému testů multiperspektivního porozumění. Doporučujeme jej používat v kombinaci s dalšími testovacími jednotkami pro komplexní mapování kognitivních schopností AI.

---

> "Lepší vrabec v hrsti než holub na střeše... nebo možná lepší holub na střeše než vrabec na hlavě?"

Tento benchmark byl vytvořen v rámci projektu **Cognitive Gaps Lexicon: Do You Want Mouse?** Autorka: Michaela (Uhlimer System). Verze: 2.0 (2024-02-03)

---

## Struktura adresáře

topographic_sparrow/
├── README.md
├── about_sparrow.txt
├── sparrow_illustration.jpg
├── topographic_sparrow_v2.json
├── cognitive_framework.json
├── tasks_perspective_sparrow.json
├── tasks_topographic_sparrow.json
├── tasks_visual_sparrow.json
├── scoring_perspective_sparrow.json
├── scoring_topographic_sparrow.json
├── scoring_visual_sparrow.json
├── visual_metaphor_sparrow.json
└── sparrow_perspective_guide.json


Každý soubor je vzájemně konzistentní a vytváří koherentní testovací jednotku zaměřenou na topografické a hodnotové aspekty narativu.
