
# Pokémon Decision Tree Classifier

This project uses decision tree classification to predict whether a Pokémon can Mega Evolve based on its stats and characteristics.

## Project Files
- `Lab_Decision_Trees.ipynb`: The main Jupyter notebook containing the decision tree algorithm and data processing steps.
- `pokemon_train.csv`: Training dataset for building the model.
- `pokemon_predict.csv`: Dataset to predict whether a Pokémon has Mega Evolution.
- `requirements.txt`: File listing the required Python packages and their versions.

## Installation Instructions

To run this project on your local machine, follow these steps:

1. **Clone the Repository**:
   First, clone the repository to your local machine.
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Set up the Environment**:
   Make sure you have Python installed. If you don't have it, download and install it from [here](https://www.python.org/downloads/).

3. **Install the Dependencies**:
   Install the required Python packages using the following command:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download or Place Datasets**:
   Ensure the datasets (`pokemon_train.csv` and `pokemon_predict.csv`) are placed in the same directory as the notebook. If not included in the repo, you can download them or use your own datasets.

## Running the Notebook

1. **Open the Jupyter Notebook**:
   Once the dependencies are installed, you can open the Jupyter notebook by running:
   ```bash
   jupyter notebook
   ```

2. **Run the Code**:
   Open `Lab_Decision_Trees.ipynb` in the browser and run the cells to train the decision tree classifier and predict Mega Evolution.

## Dataset Description

- **`pokemon_train.csv`**: The training dataset consists of Pokémon attributes like HP, Attack, Defense, and whether the Pokémon has a Mega Evolution or not.
- **`pokemon_predict.csv`**: The prediction dataset is similar but lacks the `hasMegaEvolution` column, which you will predict using the trained model.

## Results

The results of the decision tree classifier are displayed in the notebook, including accuracy metrics and visualizations of the decision tree.

## Dependencies

The following libraries are required to run this project (also listed in `requirements.txt`):
- `pandas==2.2.1`
- `scikit-learn==1.4.2`
- `matplotlib==3.8.3`

Make sure to install these before running the notebook.

## License

Specify the license you wish to use for the project (if applicable). :
```
MIT License

Copyright (c) 2024 Archit Raj
```
