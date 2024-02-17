# cloud-computing-lab
lab support for Cloud Computing

Step 01: Create and activate virtaul environment
```
Example 01:

- Create Virtual Environment
    python -m venv venv_machine_learning_project

- Activate Created Virtual Environment
    For unix based system -> source ./venv_machine_learning_project/bin/activate
    For windows -> ./venv_machine_learning_project/Scripts/activate

Example 02:

- Create Virtual Environment
    conda create -n venv_machine_learning_project

- Activate Created Virtual Environment
    conda activate venv_machine_learning_project
```
Step 02: Follow the below directory structure for your project

## Folder Structure:


```
project_name/
│
├── data/
│ ├── raw/ # Raw data files
│ ├── processed/ # Processed data files
│ └── external/ # External datasets
│
├── notebooks/ # Jupyter notebooks
│
├── src/ # Source code
│ ├── models/ # Trained models
│ ├── utils/ # Utility functions
│
├── reports/ # Reports, visualizations, and documentation
│
├── README.md # Project description and instructions
├── requirements.txt # Python dependencies
└── .gitignore # Files and directories to ignore
```


## Python Environment (**requirements.txt**):

You can use **requirements.txt** to specify the Python packages required for your project. Here's an example:

```
pip install -r requirements.txt
```
