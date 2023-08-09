# Antibiotic Resistance Prediction Tool

This repository contains a Python application with a user interface (UI) for predicting cephalosporin, piperacillin/tazobactam, trimethoprim/sulfamethoxazole, fluoroquinolone, and carbapenem resistance probabilities based on patient data.

## Content

* UI_code.ipynb
* requirements.txt
* UItoAPP.app
* model_carbapenems.pkl
* model_cephalosporins.pkl
* model_fluoroquinoles.pkl
* model_pt.pkl
* model_trim.pkl

## Installation and Usage

### Using the Standalone App (OSX)

1. **Download the App:** Download the `UItoAPP.app` file.

2. **Run the App:** Double-click the downloaded `UItoAPP.app` file to run the UI. The app will open and prompt you for input data.

3. **View Results:** The app will display the predicted probabilities for each antibiotic based on the provided input data.

### Running the Code (All Platforms)

1. **Clone the Repository:** Clone this GitHub repository to your local machine using the following command:

    ```bash
    git clone https://github.com/CMI-Laboratory/UTI_AntibioticResistance_Prediction
    ```
    
3. **Navigate to Project Directory:** Move into the project's directory using the command:

    ```bash
    cd your-repo
    ```
    
4. **Install Required Packages:** Use pip to install the necessary packages in the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application:** Start the UI application by executing the following command:

    ```bash
    python UI_code.ipynb
    ```

5. **Interact with the GUI:** Once the UI is running, you can:

   - Input patient data through the UI.
   - Click the "Continue" button to generate predicted probabilities for each antibiotic from the machine learning models.


## Citation

If you find this code helpful for your research or project, please consider citing the following article:

    @article{Ant2023,
      title = {Prediction of Antibiotic Resistance in Patients with Urinary Tract Infection: Algorithm Development and Validation (Preprint)},
      author = {Ilhanli, Nevruz and Park, Se Yoon and Kim, Jae-woong and Ryu, Jee An and Yardimci, Ahmet and Yoon, Dukyong},
      journal = {JMIR},
      year = {2023},
      eprint = {JMIR Preprints},
      url = {https://preprints.jmir.org/preprint/51326},
      doi = {https://doi.org/10.2196/preprints.51326}
    }

