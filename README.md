## Citation

For further information, see

> Wang, X., Seminck, O., & Amsili, P. (2022). Investigating associative, switchable and negatable Winograd items on renewed French data sets. Actes de La Conférence Sur Le Traitement Automatique Des Langues Naturelles (TALN) PFIA 2022. Volume II: Articles Courts.

If you use this data set, please cite:

```latex
@inproceedings{wang2022,
  title = {Investigating associative, switchable and negatable
Winograd items on renewed French data sets},
  booktitle = {Actes de La {{Conf\'erence}} Sur Le {{Traitement Automatique}} Des {{Langues Naturelles}} ({{TALN}}) {{PFIA}} 2022. {{Volume II}}: {{Articles}} Courts},
  author = {Wang, Xiaoou and Seminck, Olga and Amsili, Pascal},
  year = {2022}
}
```

## 285 French Winograd items

Current version: `v1.3`

For each item:

* `english_id` -> the id of the corresponding English item in WSC285
* `french_id` -> the id of the
 item in FWSC285
* `french_text` -> the it
em with the pronoun/possessive adjective marked with `[]`
* `french_text_ready_to_be_replaced` -> the item ready for pronoun replacement
* `associative` -> if the item is associative (1 = yes, 2 = negatively associative)
* `switchable` -> if the item is switchable (1 = yes)
* `negatable` -> if the item is negatable (1 = yes)
* `negated_text` -> negated item

## Winogrande in French

The folder `winogrande_translated_for_classification` contains Winog
rande translated to French using DeepL Pro.

For information on Winogrande, see

> Sakaguchi, K., Le Bras, R., Bhagavatula, C., & Choi, Y. (2020, April). Winogrande: An adversarial winograd schema challenge at scale. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 34, No. 05, pp. 8732-8740).
