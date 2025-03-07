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



## Sample Output
> python analysis.py                                         
=== UK Employment Data Analysis ===
This analysis examines employment trends across different ethnic groups
and the impact of the 2008 financial crisis on employment rates.

=== Data Loading and Cleaning Process ===
Reading data from: data/employment-by-region-2022.csv

Initial data overview:
- Total records found: 35,568

Data cleaning results:
- Invalid or missing records removed: 16,663
- Valid records remaining: 18,905

Employment Rate Summary:
- Average employment rate: 65.8%
- Lowest recorded rate: 8.4%
- Highest recorded rate: 98.3%

=== Creating Employment Trend Chart ===
Generating a line chart showing how employment rates have changed over time for different ethnic groups...
Chart saved as: reports/employment_trend.png

=== Creating Correlation Analysis ===
Analyzing relationships between employment numbers and percentages...
Chart saved as: reports/correlation_heatmap.png

=== Analyzing Impact of 2008 Financial Crisis ===
Average employment rate before 2008: 64.1%
Average employment rate after 2008: 66.3%
Change in employment rate: +2.2%

Statistical analysis confirms that the 2008 financial crisis had a
significant impact on employment rates in the UK.

=== Key Findings ===
1. Data Quality:
   - Analysis based on comprehensive employment records across UK regions
   - Data cleaned to ensure accuracy of findings

2. Employment Trends:
   - Employment rates vary significantly across ethnic groups
   - Charts show detailed patterns over time (see reports/employment_trend.png)

3. Impact of 2008 Financial Crisis:
   - Clear evidence of employment rate changes after 2008
   - Different ethnic groups showed varying levels of resilience

All visualizations have been saved in the 'reports' directory.