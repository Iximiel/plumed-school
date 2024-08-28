# Action: MOLINFO

| Description    | Usage |
|:--------|:--------:|
| This command is used to provide information on the molecules that are present in your system. | [![used in 10 tutorials](https://img.shields.io/badge/tutorials-10-green.svg)](https://www.plumed-tutorials.org/browse.html?search=MOLINFO)[![used in 89 eggs](https://img.shields.io/badge/nest-89-green.svg)](https://www.plumed-nest.org/browse.html?search=MOLINFO) | 

## Input

The input for this action is specified using one or more of the keywords in the following table.

| Keyword |  Type | Description |
|:--------|:------:|:-----------|
| CHAIN | atoms | (for masochists ( mostly Davide Branduardi ) ) The atoms involved in each of the chains of interest in the structure |


## Further details and examples 
Information for the manual from the code would go in here 
## Syntax 
The following table describes the keywords and options that can be used with this action 

| Keyword | Type | Default | Description |
|:-------|:----:|:-------:|:-----------|
| CHAIN | input | none | (for masochists ( mostly Davide Branduardi ) ) The atoms involved in each of the chains of interest in the structure |
| STRUCTURE | compulsory | none | a file in pdb format containing a reference structure |
| MOLTYPE | compulsory | none |  what kind of molecule is contained in the pdb file - usually not needed since protein/RNA/DNA are compatible |
| PYTHON_BIN | compulsory | none |  python interpreter |
| WHOLE | optional | false |  The reference structure is whole, i |
