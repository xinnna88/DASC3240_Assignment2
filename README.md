# Assignment II: Group B

# Group member list

- WING, Yui Yan (Leader & Owner)
- CHEN, Hongxing
- CHEN, Yanyu
- LI, Yuan
- YING, Yuling

# Dataset

Each group member may choose either of the following dataset:  

**Built-in dataset**  

- `palmerpenguins::penguins`  
- `ggplot2::msleep`  
- `ggplot2::midwest`  
- `datasets::Orange`  
- `datasets::quakes`  

**Public dataset**  

BIOTIME (CC0) <https://biotime.st-andrews.ac.uk/usageGuidelines.php>  

- `BIOTIME_raw_data_192.csv` (uploaded on Canvas) (Whale data from <https://biotime.st-andrews.ac.uk/selectStudy.php?study=192>)  
- `BIOTIME_raw_data_232.csv` (uploaded on Canvas) (Fish data from <https://biotime.st-andrews.ac.uk/selectStudy.php?study=232>)  

# Introduction

This repository contains the DASC 3240 Assignment II submissions for Group B. Each group member explores a different dataset from the provided list using interactive visualizations (Plotly) and animations (gganimate) in Quarto (`.qmd`) documents.

The repository is structured as follows:

- **`README.md`** — This file; provides an overview of the project, group members, and instructions to run the code.
- **`data/`** — Folder containing all raw datasets used in this assignment (including `BIOTIME_raw_data_192.csv` and `BIOTIME_raw_data_232.csv`).
- **`L17_Assignment_CHEN-Yanyu.qmd`** — CHEN Yanyu's individual analysis of the `ggplot2::msleep` dataset, exploring how mammalian body size relates to sleep duration across different diet types and taxonomic orders.
- **`L17_Assignment_WING-YuiYan.qmd`** — WING Yui Yan's analysis of the `BIOTIME_raw_data_192` dataset, exploring annual catch trends of major whale species in the Southern Ocean from 1932 to 1980, with a focus on the impact of industrial whaling across different species and decades.
- **`L17_Assignment_LI-Yuan.qmd`** — LI Yuan's analysis of "ggplot2::midwest"
- **`L17_Assignment_CHEN-HongXing.qmd`** — CHEN Hong Xing's analysis of "palmerpenguins::penguins"
- **`L17_Assignment_YING-YuLing.qmd`** — YING Yu Ling's analysis of "BIOTIME_raw_data_232.csv"

# Member contributions

| Member | Dataset | Contribution |
|------------------------|------------------------|------------------------|
| CHEN, Yanyu | `ggplot2::msleep` | Visualization of `ggplot2::msleep` |
| WING, Yui Yan | `BIOTIME_raw_data_192` | Visualization of `BIOTIME_raw_data_192` |
| LI, Yuan | `ggplot2::midwest` | Visualization of `ggplot2::midwest` |
| CHEN, Hong Xing | `palmerpenguins::penguins` | Visualization of `palmerpenguins::penguins` |
| YING, Yu Ling | `BIOTIME_raw_data_232.csv` | Visualization of `BIOTIME_raw_data_232.csv` |

# Reference

Maria Dornelas, Laura H. Antão, Amanda E. Bates, Viviana Brambilla, Jonathan M. Chase, Cher F. Y. Chow, Ada Fontrodona-Eslava, Anne E. Magurran, Inês S. Martins, Faye Moyes, Alban Sagouis, et al. BioTIME 2.0: Expanding and Improving a Database of Biodiversity Time Series. Global Ecol Biogeogr. 2025; 34(5):e70003. https://doi.org/10.1111/geb.70003

Cao, J., Herman, A. B., West, G. B., & Bhatt, D. L. (2020). Unraveling why we sleep: Quantitative analysis reveals abrupt transition from neural reorganization to repair in early development. *Science Advances*, *6*(38), eaba0398. <https://doi.org/10.1126/sciadv.aba0398>

Meddis, R. (1983). Sleep mechanisms and functions in humans and animals. In A. Mayes (Ed.), *Sleep mechanisms and functions in humans and animals*. Van Nostrand Reinhold.

Nowak, R. N. (1991). *Walker's mammals of the world*. Johns Hopkins University Press.

Savage, V. M., & West, G. B. (2007). A quantitative, theoretical framework for understanding mammalian sleep. *Proceedings of the National Academy of Sciences*, *104*(3), 1051–1056. <https://doi.org/10.1073/pnas.0610080104>

Sievert, C. (2020). *Interactive web-based data visualization with R, plotly, and shiny*. Chapman and Hall/CRC. <https://plotly-r.com>

Smith, F. A., Lyons, S. K., Ernest, S. K. M., Jones, K. E., Kaufman, D. M., Dayan, T., Marquet, P. A., Brown, J. H., & Haskell, J. P. (2003). Body mass of late Quaternary mammals. *Ecology*, 84(12), 3403. <https://doi.org/10.1890/02-9003>

Pedersen, T. L., & Robinson, D. (2024). *gganimate: A grammar of animated graphics* (R package version 1.0.9). <https://CRAN.R-project.org/package=gganimate>

Wickham, H. (2016). *ggplot2: Elegant graphics for data analysis* (2nd ed.). Springer-Verlag. <https://ggplot2.tidyverse.org>

Zepelin, H. (1989). Mammalian sleep. In M. H. Kryger, T. Roth, & W. C. Dement (Eds.), *Principles and practice of sleep medicine* (2nd ed., pp. 30–49). Saunders.
