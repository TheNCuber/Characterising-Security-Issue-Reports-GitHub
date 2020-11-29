# Characterising Security Issue Reports on GitHub - Dataset
This folder contains the dataset used for the paper "Characterising Security Issue Reports on GitHub" by Mohammad Ghafari and Noah Bühlmann in five seperate files.
- repositories.csv
- issues.csv
- comments.csv
- manual_issues.csv
- manual_comments.csv

The first three files contain the data for the large-scale analysis, while the last two files prefixed with *"manual_"* contain the data collected during the manual analysis. The files are standardised CSV files that include headings that indicate the variable names. Whenever time durations are indicated the unit is [hours]. To be able to link the files together, repoId and issueId columns are provided additionally.

## repositories.csv
This file contains the records of all repositories with the variables prefixed by the letter "R" in table 2 of the paper.
## issues.csv
This file contains the records of all issues with the variables prefixed by the letter "I" in table 2 of the paper.
## comments.csv
This file contains the records of all comments with the variables prefixed by the letter "C" in table 2 of the paper.
## manual_issues.csv
This file contains the records of all 333 issues used for the manual analysis with the variables prefixed by the letter "I" in table 2 and table 5 of the paper.
## manual_comments.csv
This file contains the records of all 1334 comments used for the manual analysis with the variables prefixed by the letter "C" in table 2 and table 5 of the paper.
