# latinWordnet-evaluation
First evaluation of the Latin WordNet. Data and code repository for the CLiC 2019 paper submission.

## File description

#### `evaluations.csv`

List of the 100 evaluated lemmas, 25 per syntactic category (`ADJ`, `ADV`, `V`, `N`). Field description:

- `lemma`: evaluated lemma
- `pos`: part of speech
- `NoRel`: number of synsets assigned to the lemma (be those `NEW`, `COM` or `OLD`)
- `m_v`: minimum agreement
- `Mv`: maximum agreement
- `A_v`: average value
- `s_v`: standard deviation

#### `NEW_COM-acceptance.csv`

Acceptance rate of `NEW` and `COM` synsets. Field description:

- `word_id`: lemma ID
- `synset_id`: `NEW` or `COM` synset
- `NoYES`: number of raters that accepted the synset out of 5
- `NoTOTAL`: total number of raters (5)
- `acc_rate`: acceptance rate (%)

#### `OLD-acceptance.csv`



## Evaluation guidelines

