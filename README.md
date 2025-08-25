# Course Recommender Data Processing

This project contains data processing scripts and notebooks for preparing user interaction data for course recommendation models. The main functionalities include:

- Timestamp conversion and cleaning
- Session duration calculation
- Outlier filtering
- Feature engineering (e.g., lessons viewed, course completion percentage)
- Splitting data into training and testing sets

## Structure
- `/data_processed`: Outputs generated from the data_processing notebook and also files requiered to generated course recommendation.
- `/data_raw`: Raw data extracted from Google Analytics.

## Main Notebook
- `data_processing.ipynb`: Main notebook for data cleaning, feature engineering, and dataset preparation.

## Usage
1. Install dependencies from `requirements.txt`.
2. Run the notebooks or scripts as needed for your experiments.

## Requirements
See `requirements.txt` for the list of required Python packages.

## Author
- Juan Camilo Sanguino
- jc.sanguino10@uniandes.edu.co

# Citation:
To use this dataset and for a better understanding about the process used in the dataset review:

```bibtex
    @article{sanguino2022, 
    title={A course hybrid recommender system for limited information scenarios}, 
    volume={14}, 
    url={10.5281/zenodo.7304829}, number={3}, 
    journal={Journal of Educational Data Mining}, 
    author={Sanguino Perez, Juan Camilo and Manrique, Ruben Francisco and Mariño, Olga and Linares Vásquez, Mario and Cardozo, Nicolás}, 
    year={2022}, 
    month={Dec.}, 
    pages={162–188} 
}
```

## License:

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg



