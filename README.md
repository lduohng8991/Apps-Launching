# Apps-Launching  
**Warning:**  
_This setup is always tended to be a note-learning replay and never be an official analysis to be use in any circumstances._

**Quick Analysis for a Comparision in Gaming Industry**  
_This project delves into a case study on LiveOps within the gaming industry, focusing on a critical comparison between two game application versions (1.5.2 and 1.6.0) for mobile (Android) users located in Eastern Europe._
_Comparative analysis of key metrics and user behavior between the two active versions to assess the impact of the tutorial changes and the overall performance of the new update._

**How to Open Project Files**  
**Note:** Detailed instructions regarding opening these files were also provided in the original project documentation URL.

This project involves various files for data analysis and visualization. Here's how to access and run them:  
**1. Power BI Charts and Analysis (.pbix)**  
All project charts and interactive analyses are in Study_AppLaunch.pbix. Simply double-click the file (after unzipping if necessary) to open it with Power BI Desktop.

**2. Running Python Scripts for User Experiences (py_script_run_2vers.txt)**  
**Option 1: **  
To view "Users Experiences Between 2 Versions" without installing all Python packages, use an online compiler (e.g., Online Plotly Compiler):
Copy py_script_run_2vers.txt content into the compiler.

Crucially, change the data reading line:  
_df = pd.read_csv(r"C:\Users\\YOUR_NAME\\Downloads\\LaDuongHong_Aptech_ExamSem1_AppLauch\\data_appgame.csv")_  
to:  
_df = pd.read_csv("data_appgame.csv")_  
Run the script.

**Option 2: **  
If you've already had all the required packages, simply press ▶️'Run script' right into the dashboard and view the slide in another new local host tab (automatically).

**3. Jupyter Notebook File (.ipynb)**  
The compare2vers.ipynb file is a Jupyter Notebook.  
**Open Locally:** Use Anaconda (launch Jupyter Notebook) or Visual Studio Code with the Python extension.  
**Open Cloud-based:** Upload to Google Drive and open with Google Colaboratory.
