
# Video Games Success Prediction

## Project Overview
This project aims to predict the success of video games based on various features like genre, platform, publisher, and sales data. It uses machine learning techniques to analyze the dataset and predict a game's success. The notebook `df_an.ipynb` explores and preprocesses the data, building predictive models.

## Dataset
The project uses the `merged_data.csv` dataset, which contains data on various video games, including:
- Game title
- Genre
- Platform
- Sales
- Year of release
- Publisher

## Notebook
The `df_an.ipynb` Jupyter notebook includes the following:
- **Data loading and exploration**: Exploring the dataset and visualizing key trends.
- **Data cleaning**: Handling missing values, duplicates, and preprocessing data for modeling.
- **Modeling**: Applying machine learning algorithms to predict game success.

## GitBook Documentation
For detailed documentation and further insights into the project, please visit the [GitBook](https://dg-ai.gitbook.io/video-games-success-prediction).

## Installation & Usage

### Requirements
To run the project locally, make sure to install the necessary dependencies:

```
pip install -r requirements.txt
pip install gdown
```


### Running the Notebook
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/MAD-VEE/Video_Games_Success_Prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Video_Games_Success_Prediction
    ```

3. Open the Jupyter notebook:
    ```bash
    jupyter notebook df_an.ipynb
    ```

## Dataset

The dataset `merged_data.csv` is not included in the repository due to its size.  
However, the code in the notebook is designed to automatically fetch the dataset from Google Drive when executed.

## Additional Resources: `gathering_data`

The `gathering_data` folder documents the process of gathering and preparing the dataset.  
This folder is not required to run the project but is available for reference.

You can download it as a zip file from [Google Drive](https://drive.google.com/file/d/YOUR_FILE_ID/view?usp=sharing).

### License
This project is licensed under the MIT License.