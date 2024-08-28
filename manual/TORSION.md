# Action: TORSION

| Description    | Usage |
|:--------|:--------:|
| Calculate a torsional angle. | [![used in 11 tutorials](https://img.shields.io/badge/tutorials-11-green.svg)](https://www.plumed-tutorials.org/browse.html?search=TORSION)[![used in 86 eggs](https://img.shields.io/badge/nest-86-green.svg)](https://www.plumed-nest.org/browse.html?search=TORSION)|
 | **output value** | **type** |
| the TORSION involving these atoms | scalar |

## Input

The input for this action is specified using one or more of the keywords in the following table.

| Keyword |  Type | Description |
|:--------|:------:|:-----------|
| ATOMS | atoms | the four atoms involved in the torsional angle |
| AXIS | atoms | two atoms that define an axis |
| VECTORA | atoms | two atoms that define a vector |
| VECTORB | atoms | two atoms that define a vector |
| VECTOR1 | atoms | two atoms that define a vector |
| VECTOR2 | atoms | two atoms that define a vector |


## Further details and examples 
Information for the manual from the code would go in here 
## Syntax 
The following table describes the keywords and options that can be used with this action 

| Keyword | Type | Default | Description |
|:-------|:----:|:-------:|:-----------|
| ATOMS | input | none | the four atoms involved in the torsional angle |
| AXIS | input | none | two atoms that define an axis |
| VECTORA | input | none | two atoms that define a vector |
| VECTORB | input | none | two atoms that define a vector |
| VECTOR1 | input | none | two atoms that define a vector |
| VECTOR2 | input | none | two atoms that define a vector |
| NUMERICAL_DERIVATIVES | optional | false |  calculate the derivatives for these quantities numerically |
| NOPBC | optional | false |  ignore the periodic boundary conditions when calculating distances |
| COSINE | optional | false |  calculate cosine instead of dihedral |
