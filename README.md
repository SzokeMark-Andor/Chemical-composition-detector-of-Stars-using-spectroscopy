# Spectroscopic Analysis of Stellar Objects

## Overview
This repository contains a project focused on analyzing spectroscopic data to detect and quantify elements like helium, oxygen, and other particles in O and B-type stars, neutron stars, and white dwarfs. Through data processing and visualization, the project explores stellar compositions and evolution.

## Table of Contents
- [Overview](#overview)
- [Libraries Used](#libraries-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Libraries Used
- **SDSS**: Access and analyze astronomical data from the Sloan Digital Sky Survey.
- **Astropy**: Core tools for astronomical data manipulation and analysis.
- **Astroquery**: Query astronomical databases for observational data.
- **Ipyaladin**: Interactive sky visualization in Jupyter.
- **Specutils**: Tools for spectroscopic data analysis.
- **PyAutoGUI**: Automates tasks in data acquisition and processing.

## Project Structure
- **Introduction**: Brief overview of spectroscopic goals.
- **Required Libraries**: Details on libraries used.
- **Coordinate Selection**: Methodology for targeting specific galactic coordinates.
- **Data Acquisition**: Steps to query the SDSS database.
- **Analysis**: Spectral data processing and element detection.
- **Visualization**: Visualization of detected spectral lines.
- **Conclusion**: Summary of findings on stellar evolution and chemical compositions.

## Installation
To set up the environment, install required libraries:
```bash
pip install sdss astropy astroquery ipyaladin specutils pyautogui
```

## Usage
1. Open the Jupyter Notebook file `spectroscopy.ipynb`.
2. Run each cell sequentially to perform data acquisition, processing, and visualization.
3. Adjust coordinates and filter parameters as needed to customize the analysis for different regions or stellar types.

## Results
This project identifies spectral lines in various stellar classes. The findings contribute to a deeper understanding of stellar compositions and provide insights into the stages of stellar evolution.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Citation

If you use this project in your research, please cite it as follows:

### Harvard Style
Szoke, M.-A. (2024) *Chemical composition detector of stars using spectroscopy*, GitHub. Available at: [https://github.com/SzokeMark-Andor/Chemical-composition-detector-of-Stars-using-spectroscopy/tree/main](https://github.com/SzokeMark-Andor/Chemical-composition-detector-of-Stars-using-spectroscopy/tree/main).

### IEEE Format
M.-A. Szoke, “Chemical composition detector of stars using spectroscopy,” GitHub, 2024. [Online]. Available: https://github.com/SzokeMark-Andor/Chemical-composition-detector-of-Stars-using-spectroscopy/tree/main. [Accessed: Day Month Year].
