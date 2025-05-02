## Investigating the Impact of Aerial Firefighting on Rate of Wildfire Spread
This repository contains the data, analysis code, and visualizations associated with our study on the effectiveness of aerial retardant drops in reducing wildfire rate of spread (ROS). The project uses a modeling framework incorporating both real and synthetic drop data to assess suppression effectiveness and to estimate counterfactual fire behavior.

## Repository Structure
 - data/ - Folder containing all necessary datasets (drop data, fire perimeters, ros data)
 - images/ - Folder containing output plots and figures used in the paper
 - [fullRF.ipynb](fullRF.ipynb) - Trains and evaluates the full model using real and synthetic drops
 - [histogramPlots.ipynb](histogramPlots.ipynb) - Creates histograms and distribution comparisons of model features
 - [plotPerimeters.ipynb](plotPerimeters.ipynb) - Generates visualizations of fire perimeters
 - [requirements.yml](requirements.yml) - Conda environment file with all necessary dependencies
 - [synthRF.ipynb](requirements.yml) - Trains and applies the synthetic-only model for counterfactual analysis

## Getting Started
To reproduce the results or explore the data and visualizations, follow the steps below:

1. Clone the Repository
    ``` bash
    git clone https://github.com/your-username/aerial-suppression-effectiveness.git
    cd aerial-suppression-effectiveness
    ```
2. Create and Activate Environment

    We recommend using conda to manage the environment.
    ``` bash
    conda env create -f requirements.yml
    conda activate aerial-suppression
    ```
3. Run the Notebooks

    Use Jupyter Lab or Jupyter Notebook to explore or rerun the analysis:

    ```bash
    jupyter lab
    ```
    Open and run the desired notebook.

## Citation
If you use this code or dataset in your work, please cite the corresponding paper (link to paper).

## License
This project is released under the MIT License. See [LICENSE](LICENSE) for details.
