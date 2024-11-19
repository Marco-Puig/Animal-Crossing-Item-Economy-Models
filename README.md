# Animal-Crossing-Item-Economy-Models

This repository contains models and data analysis pipelines designed to optimize trading, crafting, and profit strategies for items in *Animal Crossing: New Horizons*. The project explores the in-game economy by analyzing item properties, crafting costs, and trading values to determine the best approaches for maximizing in-game profits.

## Project Overview

The notebook performs the following key tasks:

1. **Data Loading and Cleaning**:
   - Loads the dataset containing details about in-game items such as stack size, selling price, crafting costs, and acquisition methods.
   - Cleans irregular values (e.g., `NFS` or missing values) and organizes distributions for further analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Provides descriptive statistics for key item properties, including stack size, sell price, and miles cost.
   - Visualizes relationships and distributions to understand economic trends.

3. **Optimization Models**:
   - Identifies items that yield the best return on investment (ROI) for crafting or trading.
   - Highlights items with rare acquisition methods that are ideal for trading.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Required Python packages:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - Other libraries as mentioned in the notebook

Install dependencies using:

```bash
pip install -r requirements.txt
```

### Dataset

The dataset (`items.csv`) includes:
- **Item Name**: Name of the item.
- **Stack Size**: Maximum items that can be carried in a single stack.
- **Sell Price**: Bells received when sold.
- **Miles Price**: Price in Nook Miles.
- **Acquisition Method**: How the item is obtained (e.g., crafting, tree-shaking).
- **Other attributes**: Internal identifiers and rarity information.

Place the dataset in the same directory as the notebook.

### Running the Notebook

1. Open the notebook `AnimalCrossingNookDataPipeline.ipynb` in Jupyter or Google Colab.
2. Execute cells sequentially to load the dataset, clean the data, and perform the analysis.

### Results

- **Top Items for Trading**: Items with the highest trading value based on rarity and acquisition effort.
- **Optimal Crafting Items**: Items that maximize profit when crafted.
- **Insights for Item Economy**: Key patterns and strategies to leverage in-game resources effectively.

## Contributing

Contributions to improve the models or analyses are welcome! Please fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License. See `LICENSE` for details.
