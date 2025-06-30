# 📊 Online Courses Analysis – Power BI Dashboard Project

This repository showcases a full-scale Power BI dashboard project analyzing trends in recorded online courses. It helps an EdTech startup make strategic decisions about what content to launch, who to partner with, and how to improve learner engagement based on real data.

---

## 🧠 Project Summary

- 📁 **Dataset Source**: [Kaggle Dataset – Online Courses](https://www.kaggle.com/datasets/khaledatef1/online-courses/data)
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
- 🔻 **Dropped unnecessary columns**
- 🔍 **Removed nulls and invalid records**
- 🔄 **Normalized `Duration`**:
  - `"3 months"` → `180 hours`
  - `"Flexible"` → `200 hours`
- 💬 **Parsed subtitle languages**
- ✂️ **Trimmed and standardized text**
- 🔢 **Converted numeric fields**
- 📚 **Extracted and counted skills per course**

---

## 📊 Key Visuals and Insights

### 1️⃣ Course Type Distribution
- Courses dominate; Specializations are underused
- 🎯 Recommend introducing more specialization content

### 2️⃣ Course Count by Category & Sub-category
- Strong content base in `Data Science`, `Business`, `Computer Science`

### 3️⃣ Average Views by Category/Sub-category/Language
- Highest views in `Cloud Computing`, `Data Analysis`, `Leadership`

### 4️⃣ Skill Trends by Category
- Most in-demand: `Python`, `Machine Learning`, `Communication`

### 5️⃣ Language Preferences (Top 5 Categories Only)
| Category             | Top Language | Avg Views |
|----------------------|--------------|-----------|
| Computer Science     | English      | High      |
| Business             | English      | Medium    |
| Personal Development | English      | High      |
| Health               | English      | Medium    |
| Language Learning    | Spanish      | Medium    |

### 6️⃣ Subtitle Impact
- More subtitles lead to higher engagement
- 🎯 Add 5+ subtitle languages to every course

### 7️⃣ Top Instructors (Static Table)
| Instructor       | Rating | Category          |
|------------------|--------|-------------------|
| Barbara Oakley   | 5.0    | Personal Development |
| David Joyner     | 5.0    | Computer Science  |
| Andrew Ng        | 4.9    | Data Science      |

### 8️⃣ Duration vs Views
- 10–30 hours is the sweet spot
- Avoid going beyond 60 hours

### 9️⃣ Skill Variety vs Engagement
- More diverse skills = more views
- 🎯 Ensure at least 3–4 skills per course

---

## 📝 Recommendations Summary

| Area                | Recommendation                                      |
|---------------------|-----------------------------------------------------|
| Duration            | 10–30 hours is ideal                                |
| Subtitle Strategy   | 5–7 subtitle languages per course                   |
| Instructor Outreach | Target top-rated instructors                        |
| Language Focus      | Add localization to English-heavy content           |
| Skill Variety       | Ensure 3+ trending skills per course                |
| Course Types        | Launch more specializations and certificates        |

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
- 🌍 Published on Power BI Service  
- 📸 Screenshots available in `/Assets` folder  
- 🔗 [Click here to view the live dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjU5N2IyMmEtMDVmOC00OTMwLWI1ZGEtOWIxOGIxZTdhZDUzIiwidCI6IjM0YmQ4YmVkLTJhYzEtNDFhZS05ZjA4LTRlMGEzZjExNzA2YyJ9)

---

## 👤 Author

**Farhan Akhtar**  
📧 farhan654rng@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/ifarhanakhtar)

---

## 🏷️ Tags

`Power BI` `EdTech Analytics` `Online Courses` `Data Visualization` `Kaggle Project` `Dashboard` `Instructor Insights` `Data Cleaning` `Business Intelligence`
