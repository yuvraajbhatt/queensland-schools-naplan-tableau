# 🏫 Queensland School Performance Dashboard

An interactive Tableau dashboard exploring NAPLAN performance and school profile data across queensland schools. Built as part of a data visualisation unit to uncover patterns in student literacy and numeracy outcomes.

---

## 📊 Dashboard Overview

The workbook contains **4 visualisations** combined into a single interactive dashboard:

| Sheet | Type | What it shows |
|---|---|---|
| The Bar Chart | Bar Chart | Comparison of average NAPLAN scores across school sectors or states |
| The Map | Geographic Map | Spatial distribution of schools and performance metrics across Australia |
| The Scatter Plot | Scatter Plot | Relationship between ICSEA (socio-educational advantage) and student outcomes |
| The Top 10 List | Ranked List | Top 10 performing schools based on selected metric |

---

## 📁 Dataset

The data comes from **My School (ACARA)** and includes:

- **School profile** — name, suburb, state, sector (public/Catholic/independent), school type, year range
- **NAPLAN mean scores** — reading, writing, spelling, grammar & punctuation, numeracy across Years 3, 5, 7 and 9
- **ICSEA** — Index of Community Socio-Educational Advantage (measure of socioeconomic background)
- **Enrolment data** — total, boys, girls, indigenous, LBOTE (Language Background Other Than English)
- **Geographic data** — latitude, longitude, ABS remoteness area, statistical areas

---

## 🔑 Key Calculated Field

**Year 3 to 5 Reading Growth**
```
AVG([YR5READMEAN]) - AVG([YR3READMEAN])
```
Measures the average improvement in reading scores between Year 3 and Year 5 — a useful indicator of early literacy progression.

---

## 💡 Key Insights

- Schools with higher ICSEA scores tend to have stronger NAPLAN outcomes across all domains
- Geographic location (metro vs regional vs remote) shows notable differences in mean scores
- Independent schools show higher average scores, but ICSEA-adjusted comparisons reveal a more nuanced picture

---

## 🛠 Tools Used

- **Tableau Desktop** — data visualisation and dashboard design
- **Data source:** ACARA My School dataset

---

## 🚀 How to Open

1. Download the `.twbx` file
2. Open with [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/) (free)
3. The data is embedded in the packaged workbook — no separate data file needed

---

## 👤 Author

**Yuvraj Bhatt**  
[LinkedIn](linkedin.com/in/yuvraj-bhatt-b9b5301b5)· [GitHub](yuvrajbhatt9865.url)

