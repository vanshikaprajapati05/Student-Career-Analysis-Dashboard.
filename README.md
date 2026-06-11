# 🎯 Student Career & Skill Gap Analytics Dashboard

A 5-page interactive Power BI dashboard analysing student performance, career preferences, skill gaps, placement readiness, and the impact of internships and certifications on employability — based on 500 student records.

---

## 📊 Dashboard Preview

### Page 1 — Overview
![Overview](Screenshots/Screenshot%202026-06-06%20231920.png)

### Page 2 — Skill Gap Analysis
![Skill Gap](Screenshots/Screenshot%202026-06-06%20231945.png)

### Page 3 — Career Path Insights
![Career Path](Screenshots/Screenshot%202026-06-06%20232007.png)

### Page 4 — Placement Readiness
![Placement Readiness](Screenshots/Screenshot%202026-06-06%20232040.png)

### Page 5 — Internship & Experience Insights
![Internship Insights](Screenshots/Screenshot%202026-06-06%20232105.png)

---

## 📌 Key Metrics at a Glance

| Metric | Value |
|---|---|
| 👨‍🎓 Total Students | 500 |
| 💰 Average Expected Salary | ₹765.14K |
| 📊 Average CGPA | 7.49 |
| 🧠 Average Skill Score | 70 |
| 🔧 Average Skill Gap | 10 |
| ✅ Placement Ready Students | 167 (33.4%) |
| ❌ Not Ready Students | 333 (66.6%) |
| 📈 Average Readiness Score | 68 |
| 💼 Average Internships | 1.52 |
| 🏅 Average Certifications | 4.91 |

---

## 🔍 Key Findings

**Career Distribution:**
- **Data Analyst** is the most popular career path with 96 students (19.2%)
- **Software Developer** follows at 89 students (17.8%)
- **ML Engineer** is least chosen at 75 students (15%)
- Career distribution is relatively balanced across all 6 paths

**Salary Insights:**
- **Software Developer** has the highest average expected salary (~₹800K+)
- **Data Scientist** is the second highest (~₹780K+)
- **ML Engineer** has the lowest average expected salary among all paths
- Overall average expected salary across all paths: ₹765.14K

**Skill Gap Analysis:**
- Average skill gap across all students is **10 points**
- Average skill score is consistent across career paths — ranging from **69 (Data Analyst)** to **71 (Software Developer & Data Scientist)**
- Higher certifications (8–10) correlate with higher average skill scores (70–75)

**Placement Readiness:**
- Only **33.4% (167 students)** are placement ready
- **66.6% (333 students)** are not yet placement ready
- Average readiness score is **68** — consistent across all career paths
- Students with higher CGPA (8.9+) appear most frequently in the Ready category

**Internship & Experience Impact:**
- Students with **0 internships** have the highest average expected salary at ₹782.25K
- Students with **3 internships** show ₹782.07K — nearly equal
- Students with **4+ projects** show the highest average readiness score (~69)
- Average certifications of 4.91 suggests most students have completed 4–5 certifications

---

## 📋 Dashboard Pages

### 1. Overview Dashboard
High-level summary of 500 students — average salary, CGPA, skill score, career path distribution, and salary comparison across career paths.
Slicers: Age, Gender, Career Path

### 2. Skill Gap Analysis
Identifies skill strengths and improvement areas using skill gap distribution, average skill score by career path, and skill score by certifications.
Slicers: Gender, Career Path

### 3. Career Path Insights
Compares average expected salary and average skill score across all 6 career paths with career distribution donut chart.
Slicers: Career Path, Gender

### 4. Placement Readiness Analysis
Evaluates student employability — placement status (Ready vs Not Ready), readiness score by career path, and detailed student-level data table.
Slicers: Gender, Career Path, Internships

### 5. Internship & Experience Insights
Analyses the impact of internships, certifications, and projects on skill scores, expected salary, and readiness scores.
Slicers: Career Path, Internships, Certifications, Projects

---

## 🗂️ Dataset Features

| Feature | Description |
|---|---|
| `Student ID` | Unique student identifier |
| `Gender` | Male / Female |
| `Age` | Student age (18–21) |
| `CGPA` | Cumulative Grade Point Average |
| `Python Score` | Python skill score |
| `SQL Score` | SQL skill score |
| `Power BI Score` | Power BI skill score |
| `Excel Score` | Excel skill score |
| `Machine Learning Score` | ML skill score |
| `Communication Score` | Soft skill score |
| `Projects` | Number of projects completed |
| `Internships` | Number of internships completed |
| `Certifications` | Number of certifications earned |
| `Career Path` | Preferred career (6 paths) |
| `Expected Salary` | Expected salary in ₹ |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard design & visualisation |
| Microsoft Excel | Data source (.xlsx) |
| DAX | Calculated measures & KPI cards |
| Power Query | Data transformation & cleaning |
| Data Modelling | Relationships between tables |

---

## 📁 Project Structure

```
Student-Career-Analysis-Dashboard/
├── Student Career Analysis.pbix     ← Power BI dashboard (5 pages)
├── student_career_analysis.xlsx     ← source dataset (500 records)
├── Screenshots/                     ← dashboard page screenshots
│   ├── Screenshot 2026-06-06 231920.png  ← Overview
│   ├── Screenshot 2026-06-06 231945.png  ← Skill Gap
│   ├── Screenshot 2026-06-06 232007.png  ← Career Path
│   ├── Screenshot 2026-06-06 232040.png  ← Placement Readiness
│   └── Screenshot 2026-06-06 232105.png  ← Internship Insights
└── README.md
```

---

## 🚀 How to Run

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repository
```bash
git clone https://github.com/vanshikaprajapati05/Student-Career-Analysis-Dashboard.git
```
3. Open `Student Career Analysis.pbix` in Power BI Desktop
4. Explore all 5 dashboard pages using interactive slicers and filters

---

## 🔮 Future Improvements

- Add real student data from college placement records for production-level insights
- Include time-series analysis to track skill improvement over semesters
- Build a Placement Readiness Score predictor using Python ML model
- Add drill-through pages for individual student profile deep-dive
- Connect to live Excel/Google Sheets for real-time data refresh

---

👩‍💻 Author

Vanshika Prajapati — B.Sc. Computer Science
GitHub · LinkedIn

