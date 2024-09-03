# AI-Generated Analysis Report
## Project Overview
This project aims to generate a comprehensive analysis report on the distribution of medals across different countries using Python. The report includes descriptive statistics, visualizations, and textual summaries of the analysis, all compiled into a structured PDF document. The primary goal is to automate the creation of analytical reports using AI, focusing on sports data, particularly the distribution of medals.

## Features
1. Data Loading and Preprocessing: Load and preprocess the dataset containing medal counts for various countries.
2. Statistical Summary: Compute descriptive statistics of the medal distribution, including mean, standard deviation, and percentiles.
3. Visualizations: Generate visualizations like histograms and bar charts to explore the distribution of total medals, top performers, and comparisons between medal types.
4. AI-Generated Text Summaries: Automatically generate textual explanations of the analysis using a pre-trained language model.
5. PDF Report Generation: Compile the entire analysis into a structured PDF report with sections, tables, images, and AI-generated text.

## Installation
To run this project locally, you will need to have Python installed. Follow the steps below:

## 1. Clone the Repository
```bash
git clone https://github.com/DhruvGandhi31/AI-Report-Generator.git
cd AI-Report-Generator
```

## 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

## 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## 4. Download the Pre-trained Model
```bash
python -c "from transformers import pipeline; pipeline('text-generation', model='gpt2')"
```

This command will download the GPT-2 model used for text generation.

# Usage
1. Prepare Your Data
Ensure that your dataset (cleaned_data.csv) is in the root directory of the project. The dataset should contain columns for Country, Gold, Silver, Bronze, and Total.

2. Run the Analysis Script
To generate the report, run the following script:
```bash
python generate_report.py
```
This will execute the entire analysis pipeline and save the output as analysis_report.pdf in the project directory.

3. View the Report
After running the script, you can view the generated PDF report by opening analysis_report.pdf in any PDF viewer.
