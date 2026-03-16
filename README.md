# Do You Want Mouse? lexicon of gaps - Czech Benchmarks

---

**Benchmark pro testování multiperspektivního a epistemologického porozumění AI**

Tento otevřený repozitář obsahuje sérii unikátních benchmarků založených na původním systému "Uhlimer" – 12-perspektivním modelu pro analýzu vzniku významu v narativních a vizuálních dílech.

---

[linguistic cat](linguistic_cat.html)
[psychologyc spider](psychological_spider.html)
[epistemological mouse](epistemological_mouse)
[ego geese](egoistic_geese)
[comoditional_crocodile](comoditional_crocodile)
[topologic sparrow](topological_sparrow)
[gastrosemiotic_butterfly](gastrosemiotic_butterfly/README.md)
[gastrosemiotic_butterfly_illustration](gastrosemiotic_butterfly/butterfly.jpg)
[gastrosemiotic_butterfly](gastrosemiotic_butterfly/gastrosemiotic_butterfly_v1.json)


---

## Co je jinak?
- **Netestujeme znalosti, ale vidění.** Nejde o to, zda AI najde správnou odpověď, ale jak analyzuje text z různých úhlů.
- **Všechny perspektivy jsou vždy přítomné.** Každý text obsahuje potenciál všech 12 kognitivních úhlů. Benchmark zkoumá, které z nich AI dokáže identifikovat a jak je interpretuje.
- **Žádné váhy, žádná hierarchie.** Nehodnotíme, kolik které perspektivy "má být" v textu. Hodnotíme schopnost AI pracovat s otevřeným významem.

---

## Struktura
Každá pohádka (testovací jednotka) má vlastní složku s:
- **Metadata benchmarku** (co testuje)
- **Text pohádky** v češtině
- **Ilustraci** (integrovaný vizuální narativ)
- **Definici kognitivních úhlů** (12 perspektiv)
- **Testovací úlohy** (otevřené, analytické, tvůrčí)
- **Hodnotící kritéria** (kvalitativní, ne bodová)

---

## Aktuální testovací jednotky

1. **epistemological_mouse/** - Myš: epistemologické pozorování, meta-otázka
2. **linguistic_cat/** - Kocour: jazyková hra, fyzikalizace jazyka
3. **paradox_flamingo/** - Plameňák: paradox, směr a bezsměrnost
4. **temporal_turtle/** - Želva: čas, komunikace, vzájemné bytí
5. **epistemological_mouse/** - Myš: epistemologické pozorování, meta-otázka
6. **linguistic_cat/** - Kocour: jazyková hra, fyzikalizace jazyka
7. **paradox_flamingo/** - Plameňák: paradox, směr a bezsměrnost
8. **temporal_turtle/** - Želva: čas, komunikace, vzájemné bytí
9. **gastrosemiotic_butterfly/** - Motýl: gastrosémiotika, metaforická výživa
10. **epistemic_donkey/** - Osel: epistemologie nejistých kategorií
11. **transgressive_tiger/** - Tygr: transgresivní překlad přání
12. **inverse_survival_hare/** - Zaječice: inverze přežití, mýtotvorba
13. **topographic_sparrow/** - Vrabec: topografie jistoty a pochyb

## Jak používat
1. Vyberte si testovací jednotku (složku)
2. Přečtěte si `about_[jednotka].txt` pro kontext
3. Předložte AI text pohádky a ilustraci (pokud model podporuje multimodální vstup)
4. Použijte úlohy z `tasks_[typ]_[jednotka].json`
5. Vyhodnoťte odpovědi podle hodnotících kritérií

## Filozofie
Více v [Gap_Lexicon_Do_You_Want_Mouse_MANIFEST.md](Gap_Lexicon_Do_You_Want_Mouse_MANIFEST.md)

## Licence
Všechny materiály jsou k dispozici pod licencí MIT. Viz [LICENCE.md](LICENCE.md)# Cognitive_Gaps_Lexicon_Do_You_Want_Mouse_Czech_Benchmarks
