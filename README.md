# latinWordnet-evaluation
First evaluation of the Latin WordNet. Data and code repository for the CLiC-it 2019 paper submission (see Citation below).

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

- `word_id`: lemma ID
- `synset_id`: `OLD` synset
- `NoYES`: number of raters that accepted the synset out of 5
- `NoTOTAL`: total number of raters (5)
- `acc_rate`: acceptance rate (%)

## Citation

Franzini Greta, Peverelli Andrea, Ruffolo Paolo, Passarotti Marco, Sanna Helena, Signoroni Edoardo, Ventura Viviana, Zampedri Federica. 2019. 'Nunc Est Aestimandum: Towards an Evaluation of the Latin WordNet'. In Bernardi Raffaella, Navigli Roberto, Semeraro Giovanni (eds.) _Proceedings of the Sixth Italian Conference on Computational Linguistics (CLiC-it 2019)_, 13-15 November, Bari. Accademia University Press, Torino. ISBN: 979-12-80136-00-8. DOI: [10.5281/zenodo.3518774](https://zenodo.org/record/3518774)
