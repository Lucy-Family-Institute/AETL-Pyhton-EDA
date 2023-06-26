# Python for Data Analysis and Visualization

Instructions to download and install necesaary software and data:

### 1. Installing Python

   In this workshop, we will be using Python 3 with some of its most popular scientific libraries. Although one can install a plain-vanilla Python and all required libraries by hand, we recommend installing [Anaconda](https://www.anaconda.com/), a Python distribution that comes with everything we need for the workshop. Detailed installation instructions for various operating systems can be found on [Anaconda documentation](https://docs.anaconda.com/free/anaconda/install/).

### 2. Obtain workshop materials
  - Visit the Netflix Movies and TV Shows dataset page on Kaggle:  [netflix_titles](https://www.kaggle.com/shivamb/netflix-shows)
  - Click on the "Download" button to download the dataset file (e.g., netflix_titles.csv)
  - Create a folder named lucy-python on your Desktop.
  - Move the downloaded csv file to the lucy-python folder.

### 3. Launch Python Interface - Jupyter Notebook

  To start working with Python, we need to launch a program that will interpret and execute our Python commands. A Jupyter Notebook provides a browser-based interface for working with Python. If you installed Anaconda, you could launch a notebook in two ways:

#### Anaconda Navigator
1. Launch Anaconda Navigator. It might ask you if you’d like to send anonymous usage information to Anaconda developers:
    ![Anaconda Navigator](https://drive.google.com/uc?export=view&id=1OHAbovkW5oreocpIPPEMqKKRVeiMnaNi)
    Make your choice and click the “Ok, and don’t show again” button.

2. Find the “Notebook” tab and click on the “Launch” button:
   ![Jupyter Notebook](https://drive.google.com/uc?export=view&id=1eHrMxnCeUJSNsG2kh8VVxgixWMdLNfUg)
  Anaconda will open a new browser window or tab with a Notebook Dashboard showing you the contents of your Home (or User) folder.

3. Navigate to the lucy-python directory by clicking on the directory names leading to it: Desktop, lucy-python,
  ![](https://drive.google.com/uc?export=view&id=16p4-RwC94aQS8_6005rt551WUlx5hTnN)

4. Launch the notebook by clicking on the “New” button and then selecting “Python 3”:
  ![](https://drive.google.com/uc?export=view&id=17fsB8L5mWBOJyKuyDeCKNsvgKRP8T6CG)

#### Command line(Terminal)
1. Navigate to the **lucy-python** directory:
  - **Unix shell:** If you are using Unix shell application, such as Terminal app in macOS, Console or Terminal in Linux, or Git Bash on Windows, execute the following command:

    `cd ~/Desktop/lucy-python`
  - **Command Prompt(Windows):** On Windows, you can use its native Command Prompt program. The easiest way to start it up is pressing Windows Logo Key+R, entering cmd, and hitting Return. In the Command Prompt, use the following command to navigate to the data folder:

    `cd /D %userprofile%\Desktop\lucy-python`

2. Start Jupyter Notebook:
- **Unix shell:** execute the following command:

  `jupyter notebook`

 - **Command Prompt(Windows):** execute the following command

    `python -m notebook`

3. Launch the notebook by clicking on the "New" button on the right and selecting "Python 3" from the drop-down menu:
  ![](https://drive.google.com/uc?export=view&id=17fsB8L5mWBOJyKuyDeCKNsvgKRP8T6CG)
