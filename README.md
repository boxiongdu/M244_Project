# M244 Project

This repository contains our group final project for Vassar College's **MATH-244 Intermediate Data Science** (Spring 2025), completed by Boxiong Du and Fei. Throughout this work, we perform data cleaning, exploratory analysis, modeling, and reporting on our chosen dataset as part of the course requirements.

## Table of Contents
- [Project Structure](#project-structure)
- [Data](#data)
- [Figures](#figures)
- [Scripts](#scripts)
- [Proposal](#proposal)
- [Report](#report)
- [Peer Review](#peer-review)
- [Presentation](#presentation)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
  
## Project Structure
```
M244_Project/
├── data/               # Raw and processed datasets
│   ├── raw/            # Original uncleaned data
│   └── cleaned/        # Processed and cleaned data ready for analysis
│
├── figures/            # Plots and visualizations generated during EDA and included in the report
│
├── scripts/            # Python/R scripts for cleaning, analysis, and modeling
│
├── proposal/           # Project proposal and planning documents
│
├── report/             # Final report files (Quarto/Markdown)
│   └── Final_Report.qmd
│
├── presentation/       # Slide deck for our project presentation
│
├── peer_review/        # Feedback and review artifacts from classmates
│
└── README.md           # This overview document
```

## Data
All datasets used in this project are stored under the `data/` directory:

- **raw/**: Contains the original, unmodified data files as obtained.
- **cleaned/**: Includes data that have been processed, filtered, and transformed for analysis. Each cleaning step is documented in the corresponding script in `scripts/`.

## Figures
The `figures/` folder houses all visualizations produced during EDA, including scree plots, correlation matrices, and model diagnostics. These figures are referenced in our final report.

## Scripts
All preprocessing, analysis, and modeling code lives in the `scripts/` directory.

Each script is documented with comments and can be run sequentially to reproduce our analysis.

## Proposal
Our project proposal, including research questions, hypotheses, and planned methodology, is available in the `proposal/` folder.

## Report
The final write-up is located in `report/Final_Report.qmd`. 

## Peer Review
Artifacts of our peer feedback for Eli and Caroline

## Presentation
Our slide deck summarizing the project findings can be found in the `presentation/` directory.

## Getting Started
To reproduce our results locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/M244_Project.git
   cd M244_Project
   ```
2. **Run the scripts**
   ```bash
   scripts/EDA.qmd
   ```
   Please make sure you change your file saving path accordingly.
   
3. **Build the report**
   ```bash
   quarto render report/Final_Report.qmd
   ```
   
## Dependencies
- Python 3.8+ (pandas, numpy, scikit-learn, matplotlib, seaborn)
- R 4.0+ (if applicable for certain scripts)
- Quarto (for rendering the final report)
- Git
