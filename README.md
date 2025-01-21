
<!-- ABOUT THE PROJECT -->
## About The Project

Identifying ships from satellite imagery holds great benefits for gauging supply chain activity, strengthening national defense, and monitoring port activity. This project utilizes classification models with dimensionality reduction techniques in order to find the best model to correctly label ships in satellite scenes while also being efficient enough to be completed in a timely manner. Pickle files are stored in the `models` folder and testing and training sets are stored in the `test_data` folder as csv files. No changes to the files are required to run all cells; to recreate results, one merely needs to run `test.ipynb` to recreate results, or if training is also desired, one may run `training.ipynb`. If the user wants to use a different test set, altering the `X.csv` and `t.csv` files in the `test_data` folder will allow for different test sets to be run. 

The finished formatted paper is in the `Project 2.docx` file.

The training and test files are the `training.ipynb` and `test.ipynb` files, respectively.

The updated README.md file is in the `README.md` file.

[Project 2: Dimensionality Reduction](https://github.com/UF-MLforAISystems-Fall24/project-2-undergraduate-AdamYChe)

### Running the Project

UF's HiPerGator was used to run the project, but utilizing the `environment.yml` file in the repository should allow users to run the project with the below commands.

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
   git clone https://github.com/UF-MLforAISystems-Fall24/project-1-AdamYChe.git
   ```
2. Setup (and activate) your environment
  ```sh
  conda env create -f environment.yml
  ```
3. Download [Git Large File Storage](https://git-lfs.com/)

4. Install Git Large File Storage in the cloned repository
    ```
    git lfs install
    ```
* Alternatively to Git Large File Storage, I have uploaded the pickle and csv files into the Canvas submission to download into the `models` and `test_data` folders, respectively.

<!-- Authors -->
## Authors

Adam Cheng

Project Link: [https://github.com/UF-MLforAISystems-Fall24/project-2-undergraduate-AdamYChe](https://github.com/UF-MLforAISystems-Fall24/project-2-undergraduate-AdamYChe)