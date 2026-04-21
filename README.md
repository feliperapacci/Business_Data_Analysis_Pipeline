# Business Data Analysis Pipeline

An exploration of a common data science workflow and a tour through modern tools used in industry.

## Stack

- **Python:** General purpose programming language, central to most modern data science workflows
- **pandas:** Data analysis and manipulation tool used to clean and transform the dataset
- **SQLite:** Lightweight relational database built into python, used to query data with SQL
- **scikit-learn:** Machine learning tool used to train and validate a model
- **matplotlib:** Visualization tool used to plot and present data
- **Anthropic API:** Anthropic's LLM API, used to present plain-English summaries of the dataset

## View the Notebook

A thoroughly annotated Jupyter Notebook can be accessed in [CustomerChurn.ipynb](https://github.com/feliperapacci/Business_Data_Analysis_Pipeline/blob/master/CustomerChurn.ipynb).
It can also be downloaded as an HTML file in [CustomerChurn.html](https://github.com/feliperapacci/Business_Data_Analysis_Pipeline/blob/master/CustomerChurn.html).

## Running Locally

```bash
git clone https://github.com/feliperapacci/Business_Data_Analysis_Pipeline.git
cd Business_Data_Analysis_Pipeline
pip install -r requirements.txt
```

To use the Anthropic API portion, create a `.env` file in the project directory and include your API key:

```
ANTHROPIC_API_KEY=[your_key_here]
```

Then launch Jupyter:

```bash
jupyter notebook
```
