# Tableau Projects

This repository contains a collection of Tableau dashboards and stories showcasing data visualization and analytics capabilities. The repository includes 2 comprehensive HR analytics dashboards and 1 interactive data story about the Titanic tragedy.

- **HR Analytics Dashboard demo**: [https://koval-vlad-portfolio.vercel.app/tableau/hr-analytics-dashboard](https://koval-vlad-portfolio.vercel.app//tableau/hr-analytics-dashboard)
- **Modern HR Dashboard demo**: [https://koval-vlad-portfolio.vercel.app/tableau/modern-hr-dashboard](https://koval-vlad-portfolio.vercel.app//tableau/modern-hr-dashboard)
- **Titanic Survivor Story demo**: [https://koval-vlad-portfolio.vercel.app/tableau/titanic-survivor-story](https://koval-vlad-portfolio.vercel.app//tableau/titanic-survivor-story)

## 📊 Projects Overview

### 1. HR Analytics Dashboard

**File:** `HR Analytics Dashboard/HR Analytics Dashboard.twb`  
**Preview:** `HR Analytics Dashboard/HR Analytics Dashboard.png`

![HR Analytics Dashboard](HR%20Analytics%20Dashboard/tableau-hr-dashboard.svg)

A comprehensive HR analytics dashboard focused on employee attrition analysis and workforce insights.

#### Data Source
- **File:** `HR Analytics Dashboard - dataset.xlsx`
- **Records:** 1,471 employees
- **Format:** Excel workbook

#### Key Features
- **Key Performance Indicators (KPIs):**
  - Total Employee Count: 1,470
  - Attrition Count: 237
  - Active Employees: 1,233
  - Attrition Rate: 16.12%
  - Average Age: 37

#### Visualizations & Worksheets
1. **Attrition by Gender** - Gender-based attrition analysis
2. **Attrition by Education** - Horizontal bar chart showing attrition across education fields (Life Sciences, Medical, Marketing, Technical Degree, etc.)
3. **Attrition by Gender and Age** - Multi-dimensional attrition breakdown
4. **Employee Depart Proportion** - Proportional analysis of employee departures
5. **Employees by Age** - Age distribution histogram with interactive age range filter
6. **Job Satisfaction** - Heatmap showing job satisfaction ratings (1-4) by job role
7. **KPI Dashboard** - Summary metrics display

#### Key Metrics Tracked
- Attrition rates by department, education, gender, and age
- Employee demographics (age, gender, education)
- Job satisfaction by role
- Department distribution (R&D: 65%, Sales: 30%, HR: 4%)

#### Interactive Features
- Education field filter
- Age range parameter control
- Gender distribution indicator
- PDF export functionality

---

### 2. Modern HR Dashboard

**File:** `Modern HR Dashboard/Modern HR Dashboard.twb`  
**Preview:** `Modern HR Dashboard/Modern HR Dashboard.png`

![Modern HR Dashboard](Modern%20HR%20Dashboard/tableau-modern-hr-dashboard.svg)

A modern, interactive HR dashboard providing comprehensive workforce analytics with advanced visualizations.

#### Data Source
- **File:** `dataset.csv`
- **Format:** CSV file (semicolon-delimited)
- **Fields:** Employee ID, Name, Gender, Location (State/City), Education Level, Birthdate, Hire Date, Termination Date, Department, Job Title, Salary, Performance Rating

#### Key Features
- **Overview Metrics:**
  - Active Employees: 7,984
  - Total Hired: 8,950
  - Total Terminated: 966
  - Location breakdown: HQ (70%) vs Branch (30%)

#### Visualizations & Worksheets
1. **Total Hired** - Total hiring count
2. **Total Active** - Current active employee count
3. **Total Terminated** - Termination statistics
4. **Hired By Year** - Line chart showing hiring trends over time
5. **Terminated By Year** - Line chart showing termination trends
6. **Departments** - Horizontal bar chart with hired/terminated breakdown across 7 departments (Operations, Sales, Customer Service, IT, Marketing, Finance, HR)
7. **Location** - HQ vs Branch distribution
8. **Map States** - Geographic visualization of employee distribution across US states
9. **Gender** - Gender distribution donut charts with active/terminated breakdown
10. **Age Groups** - Age demographic analysis
11. **Age vs Education** - Bubble matrix chart showing employee concentration by age group and education level
12. **Education vs Performance** - Matrix chart correlating education levels with performance ratings
13. **Gender by Education Salary** - Income analysis by gender and education
14. **Age vs Salary** - Scatter plot showing salary distribution by age with job title annotations
15. **Education Level** - Education distribution analysis
16. **Cities** - City-level employee distribution
17. **States** - State-level analysis
18. **Job Titles** - Job title breakdown
19. **Ages** - Detailed age analysis

#### Interactive Features
- Multiple filter options: Gender, Status (Hired/Terminated), Location (HQ/Branch), Hire Date
- Click-to-filter functionality on main sections
- PDF and image export capabilities
- Interactive map with state-level drill-down

#### Calculated Fields
- **Location:** Categorizes employees as HQ (New York) or Branch
- **Status:** Determines if employee is Hired or Terminated based on termination date
- **Age:** Calculated from birthdate
- **Age Groups:** Categorizes employees into age brackets
- **% Total Hired/Terminated:** Percentage calculations for hiring and termination rates

---

### 3. Who Survived Titanic Tragedy Story

**File:** `Who Survived Titanic Tragedy Story/Who Survived Titanic Tragedy Story.twb`  
**Preview Images:**
- `1.Titanic Passenger Demographics.png`
- `2.Titanic Passenger Survival Analysis.png`
- `3.Titanic Passenger Age & Fare Analysis.png`
- `4.Titanic Passenger Survivor Geography.png`
- `5.Titanic Passenger Survivor List.png`

![Titanic Survivor Story](Who%20Survived%20Titanic%20Tragedy%20Story/tableau-titanic-story.svg)

An interactive Tableau story that narrates the analysis of Titanic passenger data, exploring survival patterns and demographics.

#### Data Source
- **File:** `Titanic-Dataset.csv`
- **Format:** CSV file (comma-delimited)
- **Fields:** PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

#### Story Points

1. **Passenger Demographics** (`Demographic Profile Dashboard`)
   - Overview of passenger characteristics
   - Class distribution by embarkation port
   - Initial demographic breakdown

2. **Survival Analysis** (`Survival Analysis Dashboard`)
   - Survival rates by gender
   - Survival patterns across passenger classes
   - Family size impact on survival
   - Age group survival analysis

3. **Passenger Age & Fare Analysis** (`Age vs Fare`)
   - Scatter plot analysis of age vs. fare paid
   - Correlation between fare and survival
   - Age-based survival patterns
   - Fare bucket analysis

4. **Survivor Geography** (`Embarkation Points`)
   - Geographic visualization of embarkation ports (Cherbourg, Queenstown, Southampton)
   - Survival rates by embarkation location
   - Map-based analysis of passenger origins

5. **Survivor List** (`Survivors Embarkation Dashboard`)
   - Detailed list of survivors by embarkation port
   - Survivor counts and percentages
   - Comprehensive survivor breakdown

#### Visualizations & Worksheets
1. **Age vs Fare** - Scatter plot analysis
2. **Embarkation Points** - Geographic map visualization
3. **Fare by Class** - Fare distribution by passenger class
4. **Gender Distribution** - Gender breakdown of passengers
5. **Passengers by Age** - Age distribution histogram
6. **Passengers by Class** - Class distribution analysis
7. **Passengers class by embarkation** - Multi-dimensional breakdown
8. **Survival Rate by Fare Bucket** - Survival analysis by fare ranges
9. **Survival by Age Group** - Age-based survival patterns
10. **Survival by Family Size Group** - Family size impact on survival
11. **Survival by Gender** - Gender-based survival analysis
12. **Survivors by Embarkation** - Detailed survivor list by port
13. **Survivors by Embarkation Totals** - Aggregate survivor statistics
14. **Top 10 Passengers by Fare** - Highest fare payers
15. **Top Passengers by Fare** - Premium passenger analysis

#### Interactive Parameters
- **Survival Status:** Filter by Survived/Perished
- **Embarkation Port:** Filter by Cherbourg, Queenstown, or Southampton
- **Select Pclass:** Filter by passenger class (1st, 2nd, 3rd)
- **Minimum Age:** Age range filter
- **Age Range Parameter:** Top fare payers filter
- **High/Medium Fare Threshold:** Fare-based filtering

#### Calculated Fields
- **Passenger Count:** Total passenger count
- **Survivor Count:** Count of survivors
- **Survival Rate:** Percentage survival calculation
- **Family Size:** Calculated from SibSp and Parch
- **Family Size Group:** Categorized family sizes
- **Age Group:** Age categorization
- **IsMinor:** Boolean for minor passengers
- **High Fare Payer:** Fare threshold classification
- **Only Adult Passengers:** Adult filter flag

---

## 📁 Repository Structure

```
Tableau-Projects/
├── HR Analytics Dashboard/
│   ├── HR Analytics Dashboard.twb
│   ├── HR Analytics Dashboard.png
│   ├── HR Analytics Dashboard - dataset.xlsx
│   └── HR Analytics Dashboard.twb Files/
│
├── Modern HR Dashboard/
│   ├── Modern HR Dashboard.twb
│   ├── Modern HR Dashboard.png
│   ├── dataset.csv
│   └── Modern HR Dashboard.twb Files/
│
├── Who Survived Titanic Tragedy Story/
│   ├── Who Survived Titanic Tragedy Story.twb
│   ├── Titanic-Dataset.csv
│   ├── 1.Titanic Passenger Demographics.png
│   ├── 2.Titanic Passenger Survival Analysis.png
│   ├── 3.Titanic Passenger Age & Fare Analysis.png
│   ├── 4.Titanic Passenger Survivor Geography.png
│   └── 5.Titanic Passenger Survivor List.png
│
└── README.md
```

## 🛠️ Requirements

- **Tableau Desktop** version 18.1 or later
- **Tableau Public** (for viewing published versions)

## 📝 Usage

1. **Opening Dashboards:**
   - Open Tableau Desktop
   - Navigate to File → Open
   - Select the desired `.twb` file
   - Ensure data source files are in the correct relative paths

2. **Data Source Paths:**
   - HR Analytics Dashboard: Requires `HR Analytics Dashboard - dataset.xlsx` in the same directory
   - Modern HR Dashboard: Requires `dataset.csv` in the same directory
   - Titanic Story: Requires `Titanic-Dataset.csv` in the same directory

3. **Viewing Published Versions:**
   - The `.twbx` files (packaged workbooks) contain embedded data and can be opened directly
   - These are self-contained and don't require separate data files

## 🎨 Design Features

- **HR Analytics Dashboard:** Dark theme with vibrant color scheme (pink, green, blue)
- **Modern HR Dashboard:** Clean, modern design with light blue and grey color scheme
- **Titanic Story:** Themed storyboard with light blue background (#f0f7fa) and purple accents

## 📊 Key Insights

### HR Analytics Dashboard
- 16.12% overall attrition rate
- Highest attrition in Life Sciences (89) and Medical (63) education fields
- R&D department has the largest employee base (65%)
- Peak employee age group: 32-35 years (274 employees)

### Modern HR Dashboard
- 89% employee retention rate (11% termination rate)
- Operations department is the largest (2,429 employees)
- 70% of employees located at HQ (New York)
- Strong correlation between education level and salary

### Titanic Story
- Survival patterns reveal significant differences by gender, class, and age
- Geographic analysis shows variation in survival rates by embarkation port
- Fare amount correlates with survival probability
- Family size impacts survival outcomes

## 📄 License

This repository contains Tableau workbooks and data visualizations for educational and portfolio purposes.

## 👤 Author

Tableau visualization projects showcasing data analytics and business intelligence capabilities.

---

*Last Updated: Based on Tableau Desktop 2025.2.4 (build 20252.25.1003.1601)*
