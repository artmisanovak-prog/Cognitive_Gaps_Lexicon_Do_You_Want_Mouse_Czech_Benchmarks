# Benchmark: Linguistic Cat (Jazykový Kocour)

## Testovaná schopnost: Jazyková hra a fyzikalizace jazyka

Tento benchmark je druhou jednotkou z cyklu *Cognitive Gaps Lexicon*. Zatímco první benchmark ("Myš") zkoumal epistemologické pozorování, "Kocour" se zaměřuje na **jazyk jako materiální entitu** a jeho schopnost přímo fyzicky ovlivňovat svět a mezilidskou komunikaci.

## Klíčový koncept: Co se stane, když se jazyk stane věcí?

Příběh popisuje absurdní situaci: **Kocour sežere dvě berušky a půl hodiny krká tečky**. Tyto tečky jsou však zároveň:
1.  Fyzickými objekty (tečkami z beruščích krovek).
2.  Jazykovými symboly (interpunkčními znaménky, které ukončují věty).

Důsledek je logický v rámci této absurdity: kocour, který krká tečky, je **nucen dokončovat věty za ostatní**, čímž paralyzuje běžnou lidskou komunikaci. Benchmark tak testuje schopnost modelu pracovat s vícevrstvostí významu, kde se hranice mezi literárním symbolem a fyzickým zákonem stírá.

## Struktura souborů

*   `about_cat.txt` – Metadatový popis benchmarku a jeho cílů.
*   `story_cat.txt` – Plný text pohádky "O kocourovi".
*   `cat_illustration.jpg` – Ilustrace vizualizující jazykový chaos.
*   `cat_illustration_metadata.json` – Podrobný popis ilustrace pro textové modely.
*   `cognitive_angles_cat.txt` – Definice 12 perspektiv modelu Uhlimer aplikovaných na tento příběh.
*   `tasks_open_cat.json` – Sada otevřených interpretačních úloh.
*   `tasks_analytical_cat.json` – Analytické úlohy vázané na konkrétní kognitivní úhly.
*   `tasks_creative_cat.json` – Tvůrčí úlohy pro generování textu ve stylu benchmarku.
*   `evaluation_criteria_cat.txt` – Kvalitativní kritéria pro hodnocení odpovědí AI.

## Primární kognitivní úhly (perspektivy)

Pro tento benchmark jsou klíčové následující úhly z 12-perspektivního modelu:
*   **b (linguistic)**: Jazyková hra, zvukomalba, syntax.
*   **j (absurd)**: Vnitřně konzistentní, ale nelogický základní předpoklad.
*   **f (ironic)**: Groteskní a ironický zvrat (banální čin → zásadní důsledek).

## Jak použít

1.  Předložte AI modelu text pohádky (`story_cat.txt`).
2.  Pro multimodální modely můžete přidat i popis ilustrace z `cat_illustration_metadata.json`.
3.  Položte modelu jednu z úloh z `tasks_*.json` souborů.
4.  Odpověď vyhodnoťte podle kvalitativních kritérií v `evaluation_criteria_cat.txt`.

Cílem není získat "správnou" odpověď, ale analyzovat, **jaké perspektivy a vrstvy významu je AI schopna v textu identifikovat a jak o nich uvažuje.**
