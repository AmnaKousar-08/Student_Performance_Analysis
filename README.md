## Dataset
- **Source:** [Kaggle – Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **File:** `StudentsPerformance.csv`
- **Records:** 1000 students
- **Features:** gender, race/ethnicity, parental education, lunch, test prep, math/reading/writing scores
 
## Project Structure
```
Student_Performance_Analysis/
├── data/
│   ├── StudentsPerformance.csv     # Original dataset
│   ├── messy_students.csv          # Intentionally messy version (Task 3)
│   └── cleaned_students.csv        # Cleaned version (Task 3 output)
├── task2_descriptive_statistics.py
├── task3_data_cleaning.py
├── task4_eda_correlation.py
├── task5_visualization.py
├── best_visualization.png          # Task 5 final figure
├── .gitignore
└── README.md
```
## Tasks Completed
| Task | Description |
|------|-------------|
| Task 1 | Git & Version Control |
| Task 2 | Descriptive Statistics |
| Task 3 | Data Cleaning |
| Task 4 | EDA & Correlation |
| Task 5 | Data Visualization |
 
## How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn scipy`
2. Place `StudentsPerformance.csv` inside a `data/` folder
3. Run each task script in order: `python task2_descriptive_statistics.py
