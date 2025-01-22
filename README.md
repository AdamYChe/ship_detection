
<!-- ABOUT THE PROJECT -->
## About The Project

Identifying ships from satellite imagery holds great benefits for gauging supply chain activity, strengthening national defense, and monitoring port activity. This project utilizes classification models with dimensionality reduction techniques in order to find the best model to correctly label ships in satellite scenes while also being efficient enough to be completed in a timely manner. Pickle files are stored in the `models` folder and testing and training sets are stored in the `test_data` folder as csv files. No changes to the files are required to run all cells; to recreate results, one merely needs to run `test.ipynb` to recreate results, or if training is also desired, one may run `training.ipynb`. If the user wants to use a different test set, altering the `X.csv` and `t.csv` files in the `test_data` folder will allow for different test sets to be run. 

A finished formatted paper is in the `Ship Detection.docx` file, which contains an analysis of choices made in model training and selection, as well as offering explanations and possible next steps for future models.

The training and test files are the `training.ipynb` and `test.ipynb` files, respectively.

The updated README.md file is in the `README.md` file.

[Ship Detection](https://github.com/AdamYChe/ship_detection)

### Running the Project

Utilizing the `environment.yml` file in the repository should allow users to run the project with the below commands.

  ```sh
  conda env export > environment.yml
  ```

The user will be able to recreate it using:

  ```sh
  conda env create -f environment.yml
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/AdamYChe/ship_detection.git
   ```
2. Setup (and activate) your environment
  ```sh
  conda env create -f environment.yml
  ```
3. Download and put the following `.pkl` files in the `models` folder and the `.csv` files in the `test_data` folder.
   [lle_rand_for_model.pkl](https://drive.google.com/file/d/1uEsvDcgInucYMC-oI20BBCBsIOWe6VEk/view?usp=sharing)
   [svm_model.pkl](https://drive.google.com/file/d/18TttFMde-FBtAdqDZlu_zw8EvxXmxxRn/view?usp=sharing)
   [lle_svm_model.pkl](https://drive.google.com/file/d/1aDSbTV_VYktdO1xJtnRhqD5Hq4MQBnWi/view?usp=sharing)
   [X.csv](https://drive.google.com/file/d/1uV5hYOw_n8w_UIXorR6MHeuG2TSvWvf-/view?usp=sharing)
   [X_train.csv](https://drive.google.com/file/d/1GZ25C6FQbDEKg-sjjfp9GjTeHZFbkOdU/view?usp=sharing)

<!-- Authors -->
## Authors

Adam Cheng

Project Link: [https://github.com/AdamYChe/ship_detection](https://github.com/AdamYChe/ship_detection)
