# data-science-journey
My personal journey : Data Science

## 🚀 Journey Log

* **Day 1:** Set up my Git/GitHub repository and professional Notion journal.Today, i've set up the two most important tools in your arsenal: Git (for local version control) and GitHub (for remote backup and portfolio). You also learned and executed the fundamental add -> commit -> push cycle
* **Day 2:** Wrote my first Python script! (Variables & Data Types) - [See the code in `01_Python_Basics/`](./01_Python_Basics/Day_02_Python_Basics.ipynb)
* **Day 3:** Learned Python operators (math, logic) and my first data structure: Lists! - [See the code in `01_Python_Basics/`](./01_Python_Basics/Day_03_Operators_and_Lists.ipynb)
* **Day 4:** Learned to modify lists (`.append()`, `.pop()`) and iterate with 'for' loops. - [See the code in `01_Python_Basics/`](./01_Python_Basics/Day_04_Loops_and_List_Methods.ipynb)
* **Day 5:** Mastered dictionaries, the most important Python data structure! - [See the code in `01_Python_Basics/`](./01_Python_Basics/Day_05_Dictionaries.ipynb)
* **Day 6:** Learned to make decisions with `if/else` and write reusable code with `def`. - [See the code in `01_Python_Basics/`](./01_Python_Basics/Day_06_Conditionals_and_Functions.ipynb)
* **Day 7:** Built my first Python project! A Contact Book that combines lists, dicts, loops, and functions. - [See the code in `01_Python_Basics/`](./01_Python_Basics/Day_07_Mini_Project_Contact_Book.ipynb)
* **Day 8:** Started the "Big 3" libraries with NumPy! Learned about vectorization (fast math) and `ndarrays`. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_08_Numpy_Basics.ipynb)
* **Day 9:** Mastered NumPy 2D arrays (matrices)! Practiced indexing `[row, col]` and advanced slicing `[:, 1]`. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_09_Numpy_2D_Arrays_and_Slicing.ipynb)
* **Day 10:** Finished NumPy! Mastered boolean indexing (filtering with `data[data > 10]`) and `np.where()`. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_10_Numpy_Boolean_Indexing.ipynb)
* **Day 11:** Started Pandas! Learned about `Series`, `DataFrames`, and loaded my first dataset with `pd.read_csv()`. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_11_Pandas_Intro_DataFrames.ipynb)
* **Day 12:** Mastered Pandas selection! Sliced with `.iloc[]`, selected columns `[]`, and filtered data with `df[df['col'] > 5]`. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_12_Pandas_Selection_and_Filtering.ipynb)
* **Day 13:** Learned to modify DataFrames! Created new columns, used `df.drop()`, and handled missing data with `df.isnull().sum()`, `dropna()`, and `fillna()`. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_13_Pandas_Modifying_DataFrames.ipynb)
* **Day 14:** Learned data aggregation! Used `.describe()`, `.value_counts()`, and the powerful `df.groupby()` method. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_14_Pandas_Aggregation_and_Groupby.ipynb)
* **Day 15:** Finished Pandas! Learned to combine datasets with `pd.merge()` (SQL-like joins) and `pd.concat()`. - [See the code in `02_Data_Analysis_Libraries/`](./02_Data_Analysis_Libraries/Day_15_Pandas_Merging_and_Joining.ipynb)
* **Day 16:** Started Phase 3: Visualization! Created my first line charts with Matplotlib. - [See the code in `03_Data_Visualization/`](./03_Data_Visualization/Day_16_Matplotlib_Basics.ipynb)
* **Day 17:** Learned the difference between Bar Charts (categories) and Histograms (distribution). - [See the code in `03_Data_Visualization/`](./03_Data_Visualization/Day_17_Bar_and_Histograms.ipynb)
* **Day 18:** Learned to plot directly from Pandas! Used `df.plot(kind='scatter')` and combined `groupby()` with `df.plot(kind='bar')`. - [See the code in `03_Data_Visualization/`](./03_Data_Visualization/Day_18_Pandas_Plotting.ipynb)
* **Day 19:** Upgraded to Seaborn! Created Scatterplots with `hue` groups, linear regression models (`lmplot`), and statistical Boxplots. - [See the code in `03_Data_Visualization/`](./03_Data_Visualization/Day_19_Seaborn_Basics.ipynb)
*  **Day 20:**  Advanced Seaborn, Analogies & Styling with KDE , Heatmap and Contexts . - [See the code in '03_Data_Visualization/'](./03_Data_Visualization/Day_20_Seaborn_Advanced.ipynb)
*  **Day 21 , 22 & 23:** Beginner Phase - Capstone Project  Missing value counts and percentages calculated . - [See the code in '03_phase_beginner_capstone_project/'](./03_phase_beginner_capstone_project/Titanic_Analysis.ipynb.ipynb)


## Executive Summary: Titanic Analysis 

* **Overall:** Most passengers [approx 550 Died].
* **Gender:** [Female] had a much higher chance of survival.
* **Class:** [1st] Class passengers were more likely to survive, indicating a wealth gap.
* **Age:** Babies and young children had a [Higher] survival rate than adults.
* **Conclusion:** The strongest predictors of survival were **Female** and **1st Class**. The "Women and Children First" protocol was clearly followed, but money also played a major role.

* **Week 3: The Capstone & Visualization:** Mastered Data Visualization with Seaborn (Heatmaps, KDE, Boxplots). Completed the **Phase 1 Capstone (Titanic)**: performed full data cleaning (imputation) and EDA to identify survival drivers. **PHASE 1 COMPLETE.** (Days 15-23)

*  **Day 24:**  Introduction to Machine Learning (linear regression). - [See the code in '04_Machine_Learning/'](./04_Machine_Learning/Day_24_ML_Hello_World.ipynb)
*  **Day 25:** Simple Linear Regression (I learned why we split data: to stop the model from memorizing the answers. I built a salary predictor that estimates an $8,000 raise per year of experience.). - [See the code in '04_Machine_Learning/'](./04_Machine_Learning/Day_25_Salary_Prediction.ipynb)