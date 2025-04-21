# Tech Data Visualization

### creating a tech data visualization project using Python, Git, and `uv` virtual environments.

---

## Project Structure

### tech-viz/ `sample_data.csv`
### Input dataset (Category, Subcategory, Value) `visualize.py`
### Python script for data visualization `requirements.txt`
### Project dependencies `.gitignore`
## Output: 
### bar chart (categories) `grouped_bar_chart.png`
### grouped bar chart (subcategories) `pie_chart_category.png`
### pie chart `README.md`
### Project documentation `(this file)`



---

##  Task2 Step-by-Step

### 1. Create a GitHub Repository  
`https://github.com/your-username/tech-viz`

### 2. Create a Local Virtual Environment  
Using `uv`:

`uv venv`

This created a .venv/ directory to isolate the Python environment.

3. Connect Local Repo to Remote GitHub Repo

git init
git remote add origin https://github.com/RaneemQasim5251/tech-viz.git
git add .
git commit -m "Initial commit"
git push -u origin main

4. Create .gitignore
gitignore

# Virtual environment
venv/
.venv/

# Python cache
__pycache__/
*.pyc

# Editor and log files
.vscode/
*.log
5. Create requirements.txt
txt

pandas
matplotlib
seaborn
Install with:

uv pip install -r requirements.txt

6. Add Dataset File
File: sample_data.csv
This file contains 27 rows of categorized tech-sector data.

7. Create Python Visualization Script
File: visualize.py
The script loads data, processes it, and creates 3 visualizations using seaborn and matplotlib.

8. Run the Script
bash
نسخ الكود
python visualize.py
Charts are generated and saved as PNG files in the project root.

9. Take Screenshot of Results
Visuals generated and saved:

bar_chart_category.png
![bar_chart_category](https://github.com/user-attachments/assets/f5b8ee75-1e10-4740-8a1b-41820a7af428)

grouped_bar_chart.png
![grouped_bar_chart](https://github.com/user-attachments/assets/ae2560cd-682a-45cd-b833-2e2c5d91de0a)

pie_chart_category.png
![pie_chart_category](https://github.com/user-attachments/assets/63c92023-a198-42be-9e6c-02222ac8f4e8)

Output Visualizations
1. Total Value by Category
A horizontal bar chart showing total values for each category.


2. Subcategory Values by Category
A grouped bar chart comparing values within each category.



3. Category Share (Pie Chart)
A pie chart showing the percentage share of each category.


10. Additional Visualization:
![fig_violin_strip](https://github.com/user-attachments/assets/ae971108-e20a-4e58-a457-23dab9f83106)

