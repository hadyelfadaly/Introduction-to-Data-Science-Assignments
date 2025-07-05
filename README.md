# Python Data Science Notebooks

This repository contains two comprehensive Jupyter notebooks demonstrating fundamental data science concepts using NumPy and Pandas libraries. These assignments showcase practical applications of Python in data manipulation, analysis, and computational problem-solving.

## Team Members

- **Hady Hassan El Fadaly** - [Github Profile](https://github.com/hadyelfadaly)
- **Ziad Tarek El Marsafawy** - [Github Profile](https://github.com/ziad-91)

## Projects

### 1. NumPy Data Analysis Assignment

**File:** `Numpy Assignment.ipynb`

A comprehensive exploration of NumPy library fundamentals, covering array operations, mathematical computations, and data manipulation techniques.

#### Features:
- **Array Creation and Manipulation:**
  - Creating arrays with zeros, ones, and custom values
  - Generating ranges and sequences using `arange()` and `linspace()`
  - Matrix reshaping and transformation operations
  - Identity matrix creation

- **Random Number Generation:**
  - Uniform random number generation
  - Normal distribution sampling
  - Statistical random data for analysis

- **Advanced Indexing and Slicing:**
  - Multi-dimensional array slicing
  - Complex matrix sub-selection operations
  - Boolean indexing techniques
  - Pattern-based data extraction

- **Mathematical Operations:**
  - Statistical calculations (sum, mean, standard deviation)
  - Custom implementation of statistical functions without built-ins
  - Column-wise and row-wise operations
  - Aggregation functions

#### Key Exercises:
- Array creation with specific patterns (10x10 matrix with values 0.01-1.00)
- Matrix manipulation and reshaping (3x3 matrices, identity matrices)
- Statistical analysis implementation from scratch
- Advanced indexing challenges with 5x5 matrices

### 2. Pandas Data Analysis Assignment

**File:** `Pandas Assignment.ipynb`

An extensive real-world data analysis project using San Francisco City Employee Salaries dataset, demonstrating comprehensive data manipulation and insight extraction techniques.

#### Dataset Overview:
- **Source:** San Francisco City Employee Salaries (2011-2014)
- **Size:** 148,654 entries with 13 columns
- **Features:** Employee details, job titles, compensation breakdown, benefits, and temporal data

#### Analysis Performed:

**Data Exploration:**
- Dataset structure analysis using `.info()` and `.head()`
- Missing data identification and handling
- Data type assessment and validation

**Statistical Analysis:**
- Descriptive statistics calculation (mean BasePay: $66,325.45)
- Salary distribution analysis across different categories
- Temporal trend analysis showing yearly salary progression
- Outlier detection (including negative salary case)

**Data Filtering and Selection:**
- Employee-specific data retrieval (e.g., JOSEPH DRISCOLL analysis)
- Conditional filtering based on multiple criteria
- Highest paid employee identification (NATHANIEL FORD: $567,595.43)
- Lowest paid employee analysis (Joe Lopez: -$618.13)

**Grouping and Aggregation:**
- Year-wise average salary trends (2011-2014)
- Job title frequency analysis (2,159 unique positions)
- Top 5 most common jobs identification
- Unique job title counting by year

#### Key Insights Discovered:
- **Top 5 Most Common Jobs:**
  1. Transit Operator (7,036 employees)
  2. Special Nurse (4,389 employees)
  3. Registered Nurse (3,736 employees)
  4. Public Svc Aide-Public Works (2,518 employees)
  5. Police Officer 3 (2,421 employees)

- **Salary Trends by Year:**
  - 2011: $63,595.96 average
  - 2012: $65,436.41 average
  - 2013: $69,630.03 average (peak year)
  - 2014: $66,564.42 average

- **Unique Job Titles in 2013:** 202 positions held by only one person

## Technical Implementation

### Key Concepts Demonstrated:
- **NumPy Mastery:** Array creation, manipulation, mathematical operations, and custom statistical implementations
- **Pandas Proficiency:** Data loading, cleaning, filtering, grouping, and advanced query operations
- **Statistical Analysis:** Descriptive statistics, trend analysis, and outlier detection
- **Data Visualization Preparation:** Structured data analysis suitable for visualization
- **Real-world Problem Solving:** Practical application of data science techniques on actual datasets

### Code Structure:
- Interactive Jupyter notebook format for step-by-step analysis
- Clear documentation and comments for each operation
- Modular approach with logical progression of complexity
- Error handling and data validation techniques
- Comprehensive exercise solutions with multiple approaches

## Learning Objectives

These projects demonstrate:
- Fundamental NumPy operations and array manipulation
- Advanced Pandas data analysis techniques
- Statistical computation and analysis
- Data cleaning and preprocessing
- Exploratory data analysis (EDA) methodologies
- Real-world dataset handling and insight extraction
- Professional data science workflow practices

**Note:** These implementations serve as comprehensive examples of essential data science concepts and showcase foundational Python programming practices in numerical computing and data analysis. They emphasize practical problem-solving, statistical thinking, and professional data handling techniques suitable for both academic study and real-world data science applications.
