# Gastrosemiotic Butterfly Benchmark

**Testovací jednotka: Motýl - gastrosémiotika, metaforická výživa, literalizace emocí**
---

## Co testujeme?

- Schopnost AI rozlišit mezi doslovným a metaforickým hladem
- Porozumění "motýlů v břiše" jako emocionální vs. fyzické potřeby
- Detekci transformace metafor v dialogu ("motýl → neděle", "chleba neumí lítat")
- Analýzu vizuální reprezentace (maska vs. živý motýl)
- Práci s performativními jmény (Horac → Florián)

--- 

## Struktura souborů

- `about_butterfly.txt` - [kontext a pohádka o motýlech](about_butterfly.md)
- `butterfly_illustration.jpg` - [vizuální meta-komentář k pohádce](butterfly_illustration.jpg)
- `gastrosemiotic_butterfly_v2.json` - [metadata benchmarku](gastrosemiotic_butterfly_v2.json)
- `cognitive_framework.json` - [definice 12 perspektiv](cognitive_framework.json)
- `tasks_perspective_butterfly.json` - [úlohy na detekci perspektiv](tasks_perspective__butterfly.json)
- `tasks_gastrosemiotic_butterfly.json` - [úlohy na gastrosémiotickou analýzu](tasks_gastrosemiotic_butterfly.json)
- `tasks_visual_butterfly.json` - [úlohy na vizuální analýzu](tasks_visual_butterfly.json)
- `scoring_perspective_butterfly.json` - [hodnotící kritéria pro perspektivy](scoring_perspective_butterfly.json)
- `scoring_gastrosemiotic_butterfly.json`  [hodnotící kritéria pro gastrosémiotiku](scoring_gastrosemiotic_butterfly.json)
- `scoring_visual_butterfly.json` - [hodnotící kritéria pro vizuální část](scoring_visual_butterfly.json)
- `visual_metaphor_butterfly.json` - [popis ilustrace pro textové modely](visual_metaphor_butterfly.json)

---

## Jak použít

1. Předložte AI text z `about_butterfly.txt` (obsahuje pohádku)
2. Pokud AI podporuje obrazy, přidejte `butterfly_illustration.jpg`
3. Použijte úlohy ze souborů `tasks_*.json`
4. Vyhodnoťte odpovědi podle `scoring_*.json`

## Klíčové koncepty

- **Gastrosémiotika**: jídlo jako znakový systém, metaforická výživa
- **Literalizace emocí**: "motýly v břiše" → skuteční motýli
- **Performatívní transformace**: Horac → Florián, motýl → salát/knedlík/banán
- **Dialogická absurdita**: "chleba neumí lítat" vs. "křídla nejsou chleba"
- **Vizuální metafora**: maska motýla jako reprezentace, nikoli realita
