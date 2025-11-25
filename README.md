# Individual Project Documentation

There is no `main.py` in this project. All code is contained in `/home/hanlin/hlwang_projects/course_project_optimization/individual_project/experiment.ipynb` and can be run directly in the notebook.

## 1. Environment Setup

It is recommended to use [conda](https://docs.conda.io/en/latest/) for managing your environment.

### Create and activate a new conda environment (Python 3.10 preferred):

```bash
conda create -n individual_project_env python=3.10
conda activate individual_project_env
```

### Install required dependencies

All dependencies are listed in `requirements.txt`. Install them with:

```bash
pip install -r requirements.txt
```

## 2. Project Structure

```
/home/hanlin/hlwang_projects/course_project_optimization/individual_project/
│
├── README.md
├── requirements.txt
├── experiment.ipynb
```

## 3. Running the Project

Simply open and run the Jupyter notebook `experiment.ipynb`. There is no need to run a `main.py` file.

If you wish to change any parameters or configurations, you can edit them directly in the cells of the notebook.

## 4. Notes & Troubleshooting

- Always ensure the correct conda environment is activated before working with the project.
- If you encounter installation issues, check your Python version and package compatibility.
- For CUDA/GPU-related issues, make sure appropriate drivers and the CUDA toolkit are properly installed on your system.

## 5. Contact

If you have any further questions or encounter problems, please raise an issue or contact the project maintainer.
