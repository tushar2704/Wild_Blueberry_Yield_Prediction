# Wild Blueberry Yield Prediction

This project aims to predict the yield of wild blueberries using machine learning techniques. The dataset used for predictive modeling was generated by the Wild Blueberry Pollination Simulation Model, an open-source, spatially-explicit computer simulation program. The model allows for the exploration of various factors, such as plant spatial arrangement, outcrossing and self-pollination, bee species compositions, and weather conditions, and how they affect the pollination efficiency and yield of the wild blueberry agro-ecosystem.

## Dataset

The dataset used in this project consists of simulated data generated by the Wild Blueberry Pollination Simulation Model. This data has been validated using field observations and experimental data collected in Maine, USA, and Canadian Maritimes over the past 30 years. It serves as a valuable resource for researchers who have actual field data and those who want to experiment with machine learning algorithms on data generated by computer simulation models.

## Problem Statement

The objective of this project is to predict the yield of wild blueberries based on various features. The target variable, **yield**, is a continuous variable. The task involves classifying this variable by step-by-step analysis of the other 17 features. The evaluation metric used for model performance will be the Root Mean Squared Error (RMSE) score.

## Project Structure

    ├── LICENSE
    ├── README.md          
    ├         
    │ 
    │
    ├── reports            <- Folder containing the final reports/results of this project
    │   └── README.md      <- Details about final reports and analysis
    │ 
    │   
    ├── src                <- Source code folder for this project
        │
        ├── data           <- Datasets used and collected for this project
        │   
        ├── docs           <- Additional documentation
        │
        |── notebooks      <- Contains notebooks
        |
        ├── visualizations <- Code and Visualization dashboards generated for the project
        │
        └── results        <- Folder to store Final analysis and modelling results and code.
--------

## Installation and Setup

1. Clone the repository:

```shell
git clone https://github.com/your-username/wild-blueberry-yield-prediction.git
```

2. Install the required dependencies. It is recommended to use a virtual environment for the project:

```shell
cd wild-blueberry-yield-prediction
python -m venv venv
source venv/bin/activate (for Unix/Linux)
venv\Scripts\activate (for Windows)
pip install -r requirements.txt
```

3. Explore the project notebooks in the `notebooks` directory to understand the data analysis and model development process.

4. Run the notebooks to reproduce the results or modify them according to your requirements.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to update this README.md file with additional information specific to your project. Good luck with your Wild Blueberry Yield Prediction project!