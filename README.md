## Intro

This Github Repo contains FWSC285: adaptation to French of the famous Winograd Schema Challenge (WSC), based on the latest version in English (285 items, alias WSC285) and the first version in French (214 items, alias FWSC214) by `Amsili, P., & Seminck, O. (2017, April)`.

A machine-translated version of Winogrande (`Sakaguchi, K., Le Bras, R., Bhagavatula, C., & Choi, Y. (2020, April)`) is also provided :)

## Citation

For further information, see

> Wang, X., Seminck, O., & Amsili, P. (2022). Investigating associative, switchable and negatable Winograd items on renewed French data sets. In Traitement Automatique des Langues Naturelles (pp. 136-143). ATALA.

If you use this data set, please cite:

```latex
@inproceedings{wang-etal-2022-investigating,
    title = "Investigating associative, switchable and negatable {W}inograd items on renewed {F}rench data sets",
    author = "Wang, Xiaoou  and
      Seminck, Olga  and
      Amsili, Pascal",
    booktitle = "Actes de la 29e Conf{\'e}rence sur le Traitement Automatique des Langues Naturelles. Volume 1 : conf{\'e}rence principale",
    month = "6",
    year = "2022",
    address = "Avignon, France",
    publisher = "ATALA",
    url = "https://aclanthology.org/2022.jeptalnrecital-taln.13",
    pages = "136--143",
    abstract = "The Winograd Schema Challenge (WSC) consists of a set of anaphora resolution problems resolvable only by reasoning about world knowledge. This article describes the update of the existing French data set and the creation of three subsets allowing for a more robust, fine-grained evaluation protocol of WSC in French (FWSC) : an associative subset (items easily resolvable with lexical co-occurrence), a switchable subset (items where the inversion of two keywords reverses the answer) and a negatable subset (items where applying negation on its verb reverses the answer). Experiences on these data sets with CamemBERT reach SOTA performances. Our evaluation protocol showed in addition that the higher performance could be explained by the existence of associative items in FWSC. Besides, increasing the size of training corpus improves the model{'}s performance on switchable items while the impact of larger training corpus remains small on negatable items.",
}
```

## 285 French Winograd items

Current version: `v2.0`

For each item:

* `english_id` -> the id of the corresponding English item in WSC285
* `french_id` -> the id of the
 item in FWSC285
* `french_text` -> the item with the pronoun/possessive adjective marked with `[]`
* `english_text` -> the item in WSC285
* `french_text_ready_to_be_replaced` -> the item ready for pronoun replacement
* `associative` -> if the item is associative (1 = yes, 2 = negatively associative)
* `switchable` -> if the item is switchable (1 = yes)
* `negatable` -> if the item is negatable (1 = yes)
* `negated_text` -> negated item

## Winogrande in French

The folder `winogrande_translated_for_classification` contains Winogrande translated to French using DeepL Pro.

## References

For the first French version of Winograd items, see

> Amsili, P., & Seminck, O. (2017, April). A Google-proof collection of French Winograd schemas. In Proceedings of the 2nd Workshop on Coreference Resolution Beyond OntoNotes (CORBON 2017) (pp. 24-29).

For information on Winogrande, see

> Sakaguchi, K., Le Bras, R., Bhagavatula, C., & Choi, Y. (2020, April). Winogrande: An adversarial winograd schema challenge at scale. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 34, No. 05, pp. 8732-8740).
