# Disney Content Analysis Project

This project analyzes a dataset of Disney content to answer various questions such as identifying the focus on TV series versus films in recent years, finding similar content based on text features, and more.

## Project Overview

- **Data Analysis**: Perform exploratory data analysis (EDA) on the Disney dataset.
- **Text Matching**: Use TF-IDF and cosine similarity to identify similar content.
- **Trend Analysis**: Compare the number of TV series and movies released by Disney over the years.

## Requirements

This project uses a Python virtual environment. To set up the environment and install the necessary dependencies, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/elhamssan/analysis-project
    cd analysis-project
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv env
    ```

3. **Activate the Virtual Environment**:
    - **Windows**:
        ```bash
        env\Scripts\activate
        ```
    - **MacOS/Linux**:
        ```bash
        source env/bin/activate
        ```

4. **Install Requirements**:
    ```bash
    pip install -r dependencies.txt
    ```

## Using Jupyter Notebook

This project uses Jupyter Notebook for data analysis. It's recommended to use Jupyter Notebook inside Visual Studio Code for a better development experience.

1. **Install Jupyter**:
    ```bash
    pip install jupyter
    ```

2. **Open Jupyter Notebook in VS Code**:
    - Open VS Code.
    - Install the Jupyter extension for VS Code if not already installed.
    - Open the command palette (Ctrl+Shift+P) and select `Python: Select Interpreter` to ensure the virtual environment is selected.
    - Open the command palette again and select `Jupyter: Create New Blank Notebook` to start a new Jupyter Notebook.

## Files

- `README.md`: This file, providing an overview of the project.
- `dependencies.txt`: Contains all the dependencies required for the project.
- `.gitignore`: Ensures that the virtual environment and other unnecessary files are not included in the repository.

## .gitignore

The `.gitignore` file ensures that unnecessary files, such as the virtual environment, are not tracked by Git.