
# Trade Balance Analysis 

##  Description

This analysis focuses on analyzing the historical trade balance data of a country, which includes data on **exports**, **imports**, and **trade balance** for goods and services. The goal is to explore the patterns of trade, understand the factors contributing to trade surpluses/deficits, and visualize trends in trade metrics.

Using Exploratory Data Analysis (EDA), the project analyzes the dataset with various statistical and graphical methods. The analysis includes correlation analysis, distribution of variables, time series decomposition, and visualization of trends to uncover meaningful insights into the trade patterns over the years.

## Dataset Description

The dataset consists of the following key columns:
- **Period**: Year of the recorded trade data.
- **Balance Total**: Total trade balance (exports minus imports).
- **Balance Goods BOP**: Trade balance specifically for goods.
- **Balance Services**: Trade balance specifically for services.
- **Exports Total**: Total exports (goods and services combined).
- **Exports Goods BOP**: Exports of goods only.
- **Exports Services**: Exports of services.
- **Imports Total**: Total imports (goods and services combined).
- **Imports Goods BOP**: Imports of goods only.
- **Imports Services**: Imports of services.

## Project Structure

- **`EDA.ipynb`**: The Jupyter notebook that contains the entire code for the EDA, visualizations, and analysis of the trade data.
- **`gands.csv`**: The CSV file containing the dataset for the analysis (goods and services data).
- **`README.md`**: Instructions on how to set up and run the project.
- **`requirements.txt`**: Packages required to run this project.


## Prerequisites

To run this project locally, you'll need the following installed:

- **Python 3.x**
- **Jupyter Notebook**
- **Dependencies**

## Installation

1. Clone this repository or download the code to your local machine:
2. Install the required Python libraries mentioned in the `requirements.txt` file.
3. Ensure that you have the dataset (`gands.csv`) in the project folder.

## How to Run the Project

Steps to Run the Project in VS Code Notebook

1. Install Visual Studio Code
Download and install Visual Studio Code from the official website.

2. Install the Python Extension for VS Code
Open VS Code.
Go to the Extensions view by clicking on the square icon on the left sidebar or pressing Ctrl + Shift + X.
Search for Python and install the Python extension by Microsoft.

3. Install Jupyter Extension for VS Code
In the Extensions view, search for Jupyter and install the Jupyter extension for VS Code.
This will enable you to run Jupyter notebooks inside VS Code.

4. Set Up Python Environment
Make sure you have Python installed on your system. You can check by running:

python --version
If you don’t have Python installed, download it from here and follow the instructions.

You can also install Python using pyenv or conda if you're using virtual environments.

5. Install Required Libraries
Open a terminal in VS Code and install the reqired libraries as mentioned in requirements.txt file. 

6. Open the Jupyter Notebook in VS Code
In VS Code, navigate to the folder where your EDA.ipynb notebook is located by going to File > Open Folder and selecting the project directory.
Open the EDA.ipynb file by clicking on it from the file explorer in VS Code. It will automatically open in the Jupyter notebook interface within VS Code.

7. Select the Python Interpreter
When you open the notebook, VS Code might ask you to select a Python interpreter. Choose the appropriate Python environment where you installed the required packages.
You can also manually select it by clicking on the Python version at the bottom-left of VS Code and selecting your Python environment.

8. Run the Notebook
Once the notebook is open, you can run the cells sequentially by clicking the Run button (a triangle icon) or by pressing Shift + Enter while in a cell.
The first few cells will load the dataset, perform data cleaning, and execute the exploratory data analysis (EDA).
Continue running the cells to generate visualizations, such as time series plots, correlation heatmaps, and distribution plots.

## Conclusion

This project provides a comprehensive analysis of historical trade data, helping to uncover trends, relationships, and key areas of concern such as trade deficits. The results of the EDA can be used by policymakers, businesses, and economists to inform decisions about trade strategies and economic policies.

