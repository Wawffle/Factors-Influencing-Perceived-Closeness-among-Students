This repository contains data and code files related to a study on perceived closeness among students within a university class network. The dataset includes two CSV files:

class-names.csv: This file contains demographic information about students, such as name, gender, year of study, ethnicity, and HM status.
class-responses.csv: This file includes survey responses where students rated their perceived closeness to other students on a scale of 1 (acquaintance) to 5 (very close friend). It also indicates the rater and the selected student.

The code.Rmd file contains the R Markdown code used for data preprocessing, network analysis, and regression modeling. The code performs tasks such as data cleaning, merging datasets, creating network graphs using the igraph package, and conducting regression analysis to explore factors influencing perceived closeness.

To replicate the analysis:

1. Download or clone this repository to your local machine.
2. Open the R Markdown file (code.Rmd) in RStudio or another compatible editor.
3. Make sure to install the required R packages (igraph, tidyverse, etc.) if not already installed.
4. Run the code chunks sequentially to preprocess the data, conduct network analysis, and perform regression modeling.
5. Review the output and visualizations generated from the analysis.
