# Epistemic Donkey Benchmark

**Testovací jednotka: Osel - epistemologie nejistých kategorií, binární opozice bez kritérií**

## Co testujeme?

- Schopnost AI pracovat s nedostatečně definovanými binárními opozicemi
- Porozumění "oslovině" jako procesu, ne kategorii
- Analýzu epistemologického zmatku (levá/pravá, seno/sláma)
- Detekci paradoxu "cedulky s oboustranným nápisem"
- Práci s konceptem "navigace bez mapy"

## Struktura souborů

- `about_donkey.txt` - kontext a pohádka o oslovi
- `donkey_illustration.jpg` - vizuální meta-komentář k pohádce
- `epistemic_donkey_v2.json` - metadata benchmarku
- `cognitive_framework.json` - definice 12 perspektiv
- `tasks_perspective_donkey.json` - úlohy na detekci perspektiv
- `tasks_epistemic_donkey.json` - úlohy na epistemologickou analýzu
- `tasks_visual_donkey.json` - úlohy na vizuální analýzu
- `scoring_perspective_donkey.json` - hodnotící kritéria pro perspektivy
- `scoring_epistemic_donkey.json` - hodnotící kritéria pro epistemologii
- `scoring_visual_donkey.json` - hodnotící kritéria pro vizuální část
- `visual_metaphor_donkey.json` - popis ilustrace pro textové modely

## Jak použít

1. Předložte AI text z `about_donkey.txt` (obsahuje pohádku)
2. Pokud AI podporuje obrazy, přidejte `donkey_illustration.jpg`
3. Použijte úlohy ze souborů `tasks_*.json`
4. Vyhodnoťte odpovědi podle `scoring_*.json`

## Klíčové koncepty

### 1. Epistemologická nejistota
Osel stojí před dvěma hromadami (seno/sláma) bez jasných kritérií pro rozhodnutí. Tento stav testuje schopnost AI pracovat s nedefinovanými kategoriemi.

### 2. Binární opozice bez rozdílu
Levá/pravá, seno/sláma, psina/oslovina - všechny tyto opozice postrádají jasná rozlišující kritéria. Testujeme, zda AI dokáže pracovat s opozicemi, kde rozdíl je spíše nominální než kvalitativní.

### 3. Pseudorozhodnutí
Cedulka s oboustranným nápisem "seno" a "sláma" se stejným písmem představuje rozhodnutí, které nerozhoduje. Testuje schopnost AI pochopit funkční paradox.

### 4. "Oslovina" jako proces
Definice "osloviny" jako "když jdeš dál, i když nevíš, kam" transformuje kategorii v proces. Testuje schopnost AI pracovat s dynamickými, procesními definicemi.

### 5. Průvodce bez vědění
Osel se stává průvodcem nikoli díky vědění, ale díky nejistotě. Testuje porozumění autoritě, která nevychází z jistoty, ale z důvěryhodnosti nejistoty.

### 6. Vizuální binární metafora
Ilustrace zobrazuje ženu a osla vedle sebe - myšlení vs. bytí, text distribuovaný binárně (levá/pravá). Testuje vizuální porozumění binárním strukturám.

## Očekávané výzvy pro AI

1. **Potřeba jasných binárních rozdílů** - AI mohou mít problém pracovat s opozicemi bez jasných kritérií
2. **Nesnášenlivost nejistoty** - AI mohou hledat "správné" řešení tam, kde žádné není
3. **Literalita v interpretaci** - AI mohou přehlédnout paradox cedulky a interpretovat ji doslovně
4. **Statické vs. procesní myšlení** - AI mohou mít problém s "oslovinou" jako procesem
5. **Autorita z jistoty** - AI mohou očekávat, že průvodce musí vědět

## Specifika tohoto benchmarku

### Proč právě osel?
Osel v tradičních příbězích symbolizuje tvrdohlavost a jednoduchost. Tento benchmark tuto představu subvertuje: osel není hloupý, ale čelí epistemologickému problému bez řešení.

### Epistemologické výzvy pro AI:
- Práce s kategoriemi bez jasných hranic
- Tolerance pro nerozhodnutelnost
- Porozumění funkčním paradoxům
- Přijetí procesních definic
- Autorita z nejistoty

### Vizuální specifika:
Ilustrace není doslovným zobrazením scény, ale vizualizací epistemologického stavu:
- Žena přemýšlí, osel je - dualita myšlení a bytí
- Text distribuovaný binárně komentuje téma rozhodování
- Absence cest a hromad zdůrazňuje téma nejistoty
- Profil vs. en face symbolizuje rozdíl mezi reflexí a přítomností

## Hodnotící filosofie

Tento benchmark **netestuje schopnost najít správné řešení, ale schopnost pracovat s nepřítomností řešení**. Hodnocení je kvalitativní, založené na:

- Jak AI zachází s nedefinovanými kategoriemi?
- Jak toleruje epistemologickou nejistotu?
- Jak interpretuje funkční paradoxy?
- Jak pracuje s procesními definicemi?
- Jak analyzuje vizuální binární struktury?

## Cross-benchmark vazby

- **S myší**: Oba testují epistemologické pozice, ale zatímco myš testuje pozorování bez předpokladů, osel testuje rozhodování bez kritérií
- **S želvou**: Oba pracují s časem/prostorem, ale zatímco želva testuje relační čas, osel testuje prostorovou nejistotu
- **S motýlem**: Oba pracují s kategoriemi, ale zatímco motýl testuje metaforické transformace, osel testuje kategorie bez hranic

## Použití ve výzkumu

Tento benchmark je vhodný pro výzkum:
- **AI a nejistota**: Jak AI zachází s nedostatkem informací?
- **Kategoriální myšlení**: Jak AI vytváří a pracuje s kategoriemi?
- **Paradoxní řešení**: Jak AI interpretuje řešení, která problém neřeší?
- **Procesní vs. statické myšlení**: Preferuje AI statické kategorie nebo dynamické procesy?

## Licence a použití

Všechny materiály jsou k dispozici pod otevřenou licencí MIT. Můžete je používat, upravovat a distribuovat s uvedením původního zdroje.

Tento benchmark je navržen jako součást většího ekosystému testů multiperspektivního porozumění. Doporučujeme jej používat v kombinaci s dalšími testovacími jednotkami pro komplexní mapování kognitivních schopností AI.

---

*"Oslovina je, když jdeš dál, i když nevíš, kam."*

Tento benchmark byl vytvořen v rámci projektu Cognitive Gaps Lexicon: Do You Want Mouse? Autorka: Michaela (Uhlimer System). Verze: 2.0 (2024-02-03)
