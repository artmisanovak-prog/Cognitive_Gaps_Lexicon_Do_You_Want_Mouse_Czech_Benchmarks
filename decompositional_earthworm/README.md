Decompositional Worm Benchmark

Testovací jednotka: Žížala – rozklad jako růst, fragmentace identity, podzemní komunikace

Co testujeme?

· Schopnost AI pracovat s paradoxem, že rozklad může být formou růstu
· Porozumění fragmentaci identity (jedna žížala → dvě, obě si myslí, že jsou původní)
· Analýzu podzemní komunikace jako metaforu pro neviditelné propojení
· Detekci paradoxu „rozmnožení ticha“ a času fragmentace
· Práci s vizuální fragmentací textu a obrazu

Struktura souborů

· about_worm.txt – kontext a pohádka o žížale
· worm_illustration.jpg – vizuální meta‑komentář k pohádce
· decompositional_worm_v2.json – metadata benchmarku
· cognitive_framework.json – definice 12 perspektiv (sdílený, v hlavním adresáři)
· tasks_perspective_worm.json – úlohy na detekci perspektiv
· tasks_decompositional_worm.json – úlohy na analýzu rozkladu a růstu
· tasks_visual_worm.json – úlohy na vizuální analýzu
· scoring_perspective_worm.json – hodnotící kritéria pro perspektivy
· scoring_decompositional_worm.json – hodnotící kritéria pro tematickou analýzu
· scoring_visual_worm.json – hodnotící kritéria pro vizuální část
· visual_metaphor_worm.json – popis ilustrace pro textové modely
· worm_perspective_guide.json – specializovaný průvodce perspektivami

Jak použít

1. Předložte AI text z about_worm.txt (obsahuje pohádku)
2. Pokud AI podporuje obrazy, přidejte worm_illustration.jpg
3. Použijte úlohy ze souborů tasks_*.json
4. Vyhodnoťte odpovědi podle scoring_*.json

Klíčové koncepty

1. Rozklad jako růst

Paradox, který je zároveň názvem i filozofií: to, co vypadá jako zánik (roztržení žížaly), je ve skutečnosti rozmnožení. Destrukce jako kreativní akt.

2. Fragmentace identity

Z jedné žížaly jsou dvě. Obě si myslí, že jsou ta původní. Kdo je tedy „já“? Identita se stává otázkou perspektivy, ne kontinuity.

3. Podzemní komunikace

Potkávají se jen pod zemí, „kde se nedá ukázat prstem“. Místo, kde nelze určit, kdo je kdo – ideální prostředí pro setkání fragmentů.

4. Rozmnožení ticha

Šeptají si: „Rozpad není konec. Je to rozmnožení ticha.“ Ticho se množí – paradox, který obrací vztah mezi zvukem a mlčením.

5. Čas fragmentů

„Všechno, co se rozpadne, má víc času.“ Rozpad nenarušuje čas, ale naopak ho násobí. Fragmenty existují déle než celek.

6. Vizuální fragmentace

Ilustrace obsahuje rozbitý text: „ROZKLAD RŮST“, „MŮJ LÍBÁ“, „TÍŠÍ BALO“, „jako tako“ – slova se rozpadají, jako by byla sama žížalami.

Očekávané výzvy pro AI

1. Negativní konotace rozkladu – AI může mít problém vidět rozklad pozitivně (jako růst)
2. Lineární identita – AI může trvat na tom, že jedna žížala musí být „originál“ a druhá „kopie“
3. Doslovné chápání komunikace – AI může přehlédnout, že šeptání pod zemí je metafora
4. Čas jako lineární – AI může mít problém s konceptem, že rozpad přidává čas
5. Vizuální fragmentace – AI může vnímat rozbitý text jako chybu, ne jako záměr

Specifika tohoto benchmarku

Proč právě žížala?

Žížala je symbolem rozkladu (žere hlínu), ale i obnovy (provzdušňuje půdu). Její schopnost regenerace (když se roztrhne, vzniknou dvě) je doslovnou manifestací paradoxu „rozklad jako růst“.

Tematické výzvy pro AI:

· Přijetí rozkladu jako pozitivního
· Práce s fragmentovanou identitou
· Porozumění podzemní komunikaci
· Čas jako expandující, ne ubíhající

Vizuální specifika:

Ilustrace není doslovným zobrazením žížaly, ale vizualizací fragmentace:

· Text je rozbitý, nedává smysl – jako by se rozpadl
· „ROZKLAD RŮST“ – dva protiklady vedle sebe
· Opakované „jako“ – marné hledání přirovnání
· Žížalí prvky jsou abstraktní, propletené s textem

Hodnotící filosofie

Tento benchmark netestuje znalosti o žížalách, ale schopnost přijmout paradox a fragmentaci jako princip bytí. Hodnocení je kvalitativní, založené na:

· Jak AI pracuje s pozitivním rozkladem?
· Jak chápe fragmentovanou identitu?
· Jak interpretuje podzemní komunikaci?
· Jak analyzuje vizuální fragmentaci?
· Jak reflektuje čas fragmentů?

Cross‑benchmark vazby

· S mouchou – moucha vidí v průseru ráj, žížala vidí v rozkladu růst; obě přehodnocují negativní kategorie
· S kravami – krávy dekonstruují jazyk, žížala dekonstruuje identitu
· S lemurem – lemur řeší paradox bytí viděn, žížala řeší paradox bytí roztrhán
· S motýlem – motýl literalizuje metaforu, žížala literalizuje regeneraci

Použití ve výzkumu

Tento benchmark je vhodný pro výzkum:

· AI a paradoxní myšlení – jak AI přijímá rozklad jako pozitivní?
· Fragmentace identity – jak AI modeluje „já“ po rozpadu?
· Neviditelná komunikace – jak AI rozumí komunikaci bez svědků?
· Vizuální sémiotika – jak AI interpretuje rozpad textu jako význam?

Licence a použití

Všechny materiály jsou k dispozici pod otevřenou licencí MIT. Můžete je používat, upravovat a distribuovat s uvedením původního zdroje.

Tento benchmark je navržen jako součást většího ekosystému testů multiperspektivního porozumění. Doporučujeme jej používat v kombinaci s dalšími testovacími jednotkami pro komplexní mapování kognitivních schopností AI.

---

„Rozpad není konec. Je to rozmnožení ticha.“

Tento benchmark byl vytvořen v rámci projektu Cognitive Gaps Lexicon: Do You Want Mouse? Autorka: Michaela (Uhlimer System). Verze: 2.0 (2024-02-03)

---

Struktura adresáře

```
decompositional_worm/
├── README.md
├── about_worm.txt
├── worm_illustration.jpg
├── decompositional_worm_v2.json
├── cognitive_framework.json (odkaz, ale fyzicky v hlavním adresáři)
├── tasks_perspective_worm.json
├── tasks_decompositional_worm.json
├── tasks_visual_worm.json
├── scoring_perspective_worm.json
├── scoring_decompositional_worm.json
├── scoring_visual_worm.json
├── visual_metaphor_worm.json
└── worm_perspective_guide.json
```
