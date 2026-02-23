# ShAnEL-2

## Dataset

The ShAnEL-2 dataset can be found in the `dataset` directory, together with the file containing the participant metadata. For more details on the dataset, please refer to the corresponding paper presented at the LREC2026 conference (Degraeuwe & Moerman, in press). Please note that the dataset can be used for research purposes only.

## Dataset sources

The real-life foreign/second language (L2) learning exercises that form the basis of the ShAnEL-2 dataset come from various sources, which are referenced in the table below.

| Language | Grammar topic | Source |
| --- | --- | --- |
| NL | De indirecte rede (EN: Indirect speech) | Based on Palmer (2019) and The Dutch Online Academy (2026) |
| NL | De relative bijzin (EN: Relative clauses) | Based on Neyts et al. (2022) and NT2 TaalMenu (2026) |
| NL | Het perfectum (EN: The present perfect tense) | Based on Devos et al. (2018) |
| EN | *Can* versus *may* | Provided by Bernard De Clerck and An Baeyens |
| EN | Conditionals | Provided by Bernard De Clerck and An Baeyens |
| EN | Expressions of the future | Provided by Bernard De Clerck and An Baeyens |
| ES | El subjuntivo (EN: The subjunctive) | Provided by Patrick Goethals and Jasper Vervaeke |
| ES | Los tiempos del pasado (EN: Past tenses) | Provided by Patrick Goethals and Jasper Vervaeke |
| ES | *Ser* versus *estar* | Provided by Patrick Goethals and Jasper Vervaeke |

## Coursebook materials

In the textbook RAG setup of the LREC2026 study, real-life L2 learning textbooks were used to "augment" the prompt. For each language, we gathered course materials on three different grammar topics. All materials are copyright-protected, but we provide a small excerpt for each topic in the `preliminaryExperiments/LREC2026/courseMaterials_sample` folder. The English and Spanish materials are written primarily for learners with Dutch as their native language (L1); the Dutch materials are written independently of any L1, although sometimes they contain additional clarifications in English. The table below presents a detailed overview of the coursebook materials, including the length of the coursebook file in number of tokens.

| Language | Grammar topic | Length | Coursebook | Authors (publisher) | Full reference |
| --- | --- | --- | --- | --- | --- |
| NL | De indirecte rede (EN: Indirect speech) | 542 | 77 puntjes op de i: Perfect Nederlands voor anderstaligen | &copy; Emily Palmer (Uitgeverij Coutinho) | Palmer (2019) |
| NL | De relative bijzin (EN: Relative clauses) | 881 | ENT2R: Nederlands voor anderstaligen (Niveau 3) | &copy; Dominique Neyts, Sien Vande Ryse, and Linde Braeckman (Pelckmans) | Neyts et al. (2022) |
| NL | Het perfectum (EN: The present perfect tense) | 2,809 | Vanzelfsprekend: Nederlands voor anderstaligen | &copy; Rita Devos, Han Fraeters, Peter Schoenaerts, and Helga Van Loo (Acco) | Devos et al. (2018) |
| EN | *Can* versus *may* | 7,170 | English Grammar (E1SB) (theory + exercises) - Uitgave 2019-2020 | &copy; Bernard De Clerck and An Baeyens (Ghent University) | N/A |
| EN | Conditionals | 3,370 | English Grammar (E1SB) (theory + exercises) - Uitgave 2019-2020 | &copy; Bernard De Clerck and An Baeyens (Ghent University) | N/A |
| EN | Expressions of the future | 5,542 | English Grammar (E1SB) (theory + exercises) - Uitgave 2019-2020 | &copy; Bernard De Clerck and An Baeyens (Ghent University) | N/A |
| ES | El subjuntivo (EN: The subjunctive) | 10,317 | Spaans: Grammatica en semantiek - Uitgave 2025-2026 | &copy; Patrick Goethals and Jasper Vervaeke (Ghent University) | N/A |
| ES | Los tiempos del pasado (EN: Past tenses) | 4,882 | Spaans: Grammatica en semantiek - Uitgave 2025-2026 | &copy; Patrick Goethals and Jasper Vervaeke (Ghent University) | N/A |
| ES | *Ser* versus *estar* | 1,452 | Spaans: Grammatica en semantiek - Uitgave 2025-2026 | &copy; Patrick Goethals and Jasper Vervaeke (Ghent University) | N/A |

## Prompts

The prompts used in the LREC2026 study can be found in the `preliminaryExperiments/LREC2026/prompts` directory.

## References

- Degraeuwe, J., & Moerman, T. (in press). ShAnEL-2: A Multilingual Benchmarking Dataset for Short-Answer Language Learning Exercises.
- Devos, R., Fraeters, H., Schoenaerts, P., & Van Loo, H. (2018). *Vanzelfsprekend. Nederlands voor anderstaligen*. Acco Leuven.
- Neyts, D., Vande Ryse, S., & Braeckman, L. (2022). *ENT2R-niveau 3 Nederlands voor anderstaligen*. Pelckmans.
- NT2 TaalMenu. (2026). *NT2—B1—Grammatica—Menu Relatieve Bijzinnen*. Retrieved 23 February 2026, from https://nt2taalmenu.nl/nt2-b1-grammatica-relatieve-bijzinnen/
- Palmer, E. (2019). *77 puntjes op de i: Perfect Nederlands voor anderstaligen*. Coutinho.
- The Dutch Online Academy. (2026). *Indirecte rede Nederlands | Leer Nederlands woordvolgorde*. Retrieved 23 February 2026, from https://thedutchonlineacademy.com/grammar/indirecte-rede-het-gebruik-van-of
