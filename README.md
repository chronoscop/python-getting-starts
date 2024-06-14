# Python Getting Started Guide

This repository contains Jupyter notebooks to help beginners learn Python. The notebooks cover basic topics like data structures, getting started with Python, and loops.

## Notebooks

- **python_getting_starts.ipynb**: This notebook helps you get started with Python, covering fundamental concepts and basic syntax.
- **python_loop.ipynb**: This notebook explains loops in Python, including `for` and `while` loops with practical examples.
- **python_data_structure.ipynb**: This notebook covers basic Python data structures such as lists, dictionaries, sets, and tuples.

### Recommended Reading Order

1. **python_getting_starts.ipynb**: Begin with this notebook to understand the basics of Python and its syntax.
2. **python_loop.ipynb**: Continue with this notebook to learn about loops and how to control the flow of your programs.
3. **python_data_structure.ipynb**: Finish with this notebook to get a good grasp of the various data structures available in Python.

## Installation Guide

### Prerequisites

- A computer with an internet connection
- A development environment (we recommend Visual Studio Code)

#### Install Visual Studio Code

1. Go to the [Visual Studio Code website](https://code.visualstudio.com/).
2. Download the installer for your operating system.
3. Run the installer and follow the instructions to complete the installation.

### Step-by-Step Guide

#### 1. Install Anaconda

1. Go to the [Anaconda website](https://www.anaconda.com/products/distribution) and download the latest version of Anaconda for your operating system.
2. Run the installer and follow the instructions to complete the installation.
3. During the installation, ensure that you select the option to add Anaconda to your PATH environment variable.

#### 2. Install Jupyter Notebook Extension for VSCode

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
3. Search for "Jupyter" and click "Install" on the Jupyter extension by Microsoft.
4. Also, ensure that the Python extension by Microsoft is installed.

#### 3. Clone the Repository

1. If you do not have Git installed, download the repository as a ZIP file.

2. Extract the ZIP file to a directory of your choice.

   Alternatively, if you have Git installed, you can clone the repository by running:

   ```bash
   git clone https://github.com/chronoscop/python-getting-starts.git
   ```
   
#### 4. Create and Activate a Virtual Environment

1. Open Anaconda Prompt (Windows) or Terminal (MacOS/Linux).

2. Create a new virtual environment using the following command:

   ```bash
   conda create --name myenv python=3.8
   ```

   Replace `myenv` with the name you want for your virtual environment and python version you can choose from 3.8 to 3.11.

3. Activate the virtual environment:

   - On Windows:

     ```bash
     conda activate myenv
     ```

   - On MacOS/Linux:

     ```bash
     source activate myenv
     ```

#### 5. Open the Notebooks in VSCode

1. Open Visual Studio Code.
2. Open the folder containing the cloned repository by clicking on `File > Open Folder` and selecting the folder.
3. Open the desired notebook file (e.g., `python_getting_starts.ipynb`). The file should open in a new tab with Jupyter Notebook functionality.
4. Ensure you are using the correct Python interpreter by selecting the Anaconda environment. You can do this by clicking on the Python version displayed in the bottom left corner of the VSCode window and selecting the Anaconda interpreter.

### Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
