# UK Employment Data Analysis


## Project Overview
This analysis examines employment trends in the UK, focusing on:
- Employment rates across different ethnic groups
- Impact of the 2008 financial crisis
- Regional variations in employment


## Data Source
- **Source**: UK Government's Ethnicity Facts and Figures website
- **Dataset**: Employment by region_2022 - Spreadsheet (csv)
- **URL**: [Employment Data](https://www.ethnicity-facts-figures.service.gov.uk/work-pay-and-benefits/employment/employment/latest/#download-the-data)


## Instruction to run the analysis
1. Create and activate conda environment:
   conda create -n uk-employment python=3.8
   conda activate uk-employment

2. Install dependencies:
   pip install -r requirements.txt

3. Run the analysis:
   python analysis.py


## Instruction to remove the conda environment
   conda deactivate

   conda remove --name uk-employment --all
   
   (And remove all demo files)