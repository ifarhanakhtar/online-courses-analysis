# 📊 Online Courses Analysis – Power BI Dashboard Project

This repository showcases a full-scale Power BI dashboard project analyzing trends in recorded online courses. It helps an EdTech startup make strategic decisions about what content to launch, who to partner with, and how to improve learner engagement based on real data.

---

## 🧠 Project Summary

- 📁 **Dataset Source**: Kaggle
- 📊 **Tool Used**: Power BI Desktop
- 📌 **Focus**: Category-wise insights, skill trends, language preferences, subtitle impact, instructor ranking, and viewer engagement
- 📈 **Goal**: Help the EdTech startup grow its course offerings in alignment with viewer demand and content performance

---

## 🎯 Business Objectives

| Objective                                                                          | Outcome                                                         |
|------------------------------------------------------------------------------------|------------------------------------------------------------------|
| Analyze the distribution of course types across categories                        | Identify where to launch new course types                        |
| Count number of courses by category and sub-category                              | Find content gaps and crowded niches                             |
| Track average views per category, sub-category, and language                      | Spot high-engagement content                                     |
| Determine most-taught skills by category                                          | Align courses with in-demand job skills                          |
| Evaluate language preferences (Top 5 categories)                                  | Optimize accessibility for learners                              |
| Investigate impact of subtitles on viewership                                     | Prove need for multilingual content                              |
| Identify top 3 instructors per category/sub-category                              | Partner with quality instructors                                 |
| Analyze relationship between duration and viewer engagement                       | Recommend ideal content length                                   |
| Check if skill variety affects viewer engagement                                  | Encourage broader curriculum design                              |

---

## 🧹 Data Cleaning (Power BI Power Query)

All data transformations were performed inside **Power BI** using **Power Query Editor**.

### ✅ Key Steps:
- 🔻 **Dropped unnecessary columns** to retain only analysis-relevant fields
- 🔍 **Removed nulls and invalid records** from `Category`, `Rating`, `Language`, etc.
- 🔄 **Normalized `Duration`**:
  - `"3 months"` → `180 hours` (3 × 60)
  - `"Flexible"` → `200 hours`
  - `"4 hours"` → `4 hours`
- 💬 **Extracted subtitle count** from comma-separated values using Power Query logic
- ✂️ **Trimmed and standardized text** (e.g., English, english → English)
- 🔢 **Converted ratings, viewer counts, and durations** to numeric types
- 📚 **Split skills** and counted number of skills per course to analyze variety

---

## 📊 Key Visuals and Insights

### 1️⃣ **Course Type Distribution**
- Most courses fall under the `Courses` type
- Very few specializations or professional certificates
- 🎯 Recommendation: Pilot certificates in high-demand categories

---

### 2️⃣ **Course Count by Category & Sub-category**
- High content volume in `Data Science`, `Business`, and `Computer Science`
- Sub-category filter helps find gaps

---

### 3️⃣ **Average Views by Category, Sub-category & Language**
- `Cloud Computing`, `Data Analysis`, and `Personal Development` have top avg. views
- English dominates, but Spanish and French subtitles boost views

---

### 4️⃣ **Skill Trends by Category**
- Most popular: `Python`, `Machine Learning`, `Data Analysis`, `Leadership`
- Word cloud used to visualize skill relevance per category

---

### 5️⃣ **Language Preferences (Top 5 Categories Only)**
| Category              | Top Language | Avg Views |
|-----------------------|--------------|-----------|
| Computer Science      | English      | High      |
| Business              | English      | Medium    |
| Personal Development  | English      | High      |
| Health                | English      | Medium    |
| Language Learning     | Spanish      | Medium    |

---

### 6️⃣ **Subtitle Availability vs. Views**
- More subtitles = more views
- Courses with 5–7 subtitles show highest engagement
- 🎯 Recommendation: Always include at least 5 subtitle languages

---

### 7️⃣ **Top 3 Instructors by Category/Sub-category**
| Instructor             | Rating | Category          |
|------------------------|--------|-------------------|
| Barbara Oakley         | 5.0    | Personal Development |
| David Joyner           | 5.0    | Computer Science  |
| Andrew Ng              | 4.9    | Data Science      |
- Static table; sorted by rating and sub-category
- 🎯 Recommendation: Partner with top educators

---

### 8️⃣ **Course Duration vs Views**
- Best viewer engagement at **10–30 hours**
- Sharp drop-off after **60 hours**
- 🎯 Recommendation: Limit course length to 30 hours max

---

### 9️⃣ **Skill Variety vs Engagement**
| Category              | Avg Skills | Avg Views |
|-----------------------|------------|-----------|
| Personal Development  | 4.47       | High      |
| Health                | 3.02       | High      |
| Physical Science      | 2.89       | Medium    |
- 🎯 Recommendation: Include at least **3+ skills per course**

---

## 📝 Recommendations Summary

| Area                | Recommendation                                      |
|---------------------|-----------------------------------------------------|
| Duration            | 10–30 hours is ideal                                |
| Subtitle Strategy   | 5–7 subtitle languages per course                   |
| Instructor Outreach | Target top-rated instructors for collaborations     |
| Language Focus      | Localize English-heavy categories                   |
| Skill Variety       | Ensure 3+ trending skills in every course           |
| Course Types        | Explore growth in Specializations/Certificates      |

---

## 📂 Folder Structure

/online-courses-analysis
│
├── raw_dataset.xlsx
├── dashboard.png
├── OnlineCoursesDashboard.pbix
├── README.md
└── LICENSE

---

## 🌐 Deployment

- 🧠 Built using Power BI Desktop
- 🌍 Published on Power BI Service for public sharing
- 📸 Screenshots available in `/Assets` folder
- 🔗 Add dashboard web link here once published (e.g., Power BI public URL)

---

## 👤 Author

**Farhan Akhtar**  
📧 farhan654rng@gmail.com 
🔗 LinkedIn(https://linkedin.com/in/ifarhanakhtar)

---

## 🏷️ Tags

`Power BI` `EdTech Analytics` `Online Courses` `Data Visualization` `Kaggle Project` `Dashboard` `Instructor Insights` `Data Cleaning` `Business Intelligence`

