# COVID-19 India Project

A data analysis project focused on the COVID-19 pandemic in India. The project downloads the public Kaggle dataset `sudalairajkumar/covid19-in-india` and explores the available files for daily case trends, testing data, and vaccination statistics.

## Project Overview

This notebook-based project is designed to:

- Load COVID-19 datasets for India
- Inspect the structure of the available CSV files
- Explore state-wise and daily case trends
- Understand the dataset schema and available metrics
- Serve as a starting point for further analysis and visualizations

## Project Structure

```text
MyAnatomy/
├── Module1/
│   └── covid_19_India_Project.ipynb
├── README.md
└── (additional project files as they are added)
```

## Dataset

The project uses the Kaggle dataset:

- `sudalairajkumar/covid19-in-india`

The dataset includes files such as:

- `covid_19_india.csv`
- `StatewiseTestingDetails.csv`
- `covid_vaccine_statewise.csv`

These files contain information related to:

- Daily reported COVID-19 cases in India
- State and union territory-wise counts
- Testing details
- Vaccination statistics

## Tools and Libraries

The notebook uses Python libraries such as:

- `pandas`
- `os`
- `kagglehub`

## Setup Instructions

1. Install Python 3.8+.
2. Install the required packages:

```bash
pip install pandas kagglehub
```

3. Make sure you have access to the Kaggle dataset via Kaggle credentials or a working Kaggle API setup.
4. Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.

## Running the Project

Open the notebook in `Module1/covid_19_India_Project.ipynb` and run the cells in order.

The notebook performs the following steps:

- Downloads the Kaggle dataset
- Lists the dataset files
- Loads the main COVID dataset into a Pandas DataFrame
- Displays the data for further analysis

## Example Workflow

```python
import kagglehub

path = kagglehub.dataset_download("sudalairajkumar/covid19-in-india")
print("Path to dataset files:", path)
```

## Notes

- This project is useful for learning how to work with real-world public health datasets.
- It can be extended with data cleaning, exploratory data analysis, visualizations, and trend monitoring.
- The current notebook acts as the foundation for deeper analysis of COVID-19 patterns across Indian states.

## License

This project uses public dataset content from Kaggle. Please review the dataset license and Kaggle terms before publishing or reusing the data beyond personal learning or academic exploration.

## Future Enhancements

Potential next steps include:

- Visualizing daily confirmed, recovered, and death trends
- Comparing states and union territories
- Calculating growth rates and peaks
- Merging case data with vaccination data
- Creating interactive dashboards
