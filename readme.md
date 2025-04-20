# 📊 Technical Assessment Report – Naos Blockchain Capital

This repository contains my submission for the technical assessment task provided by **Naos Blockchain Capital**. The objective was to analyze and interpret data from various datasets related to Mexican employment and economic indicators.

---

## 📁 Files Included

- `report.pptx` – A presentation summarizing the findings, insights, and visualizations.
- `report.ipynb` – A Jupyter Notebook containing the full data analysis code and methodology.

---

## 📝 Methodology Overview

1. **Salary Analysis**
   - I used the `ce2019_nac.csv` dataset for the core analysis.
   - Two columns were used for average salaries:
     - `A747A`: Operational workers
     - `A748A`: Administrative workers  
   - These were identified via the `diccionario_de_datos_ce2019.csv` (referred to as the "main dataset").

2. **Regional Classification**
   - Initially intended to use `tc_entidad_municipio.csv` for regional mapping.
   - However, the `MUNICIPIO` column in the main dataset was empty.
   - Instead, I used the `tc_estrato_ce2019.csv`, which divides Mexico into four stratified zones and shared mutual keys with the main dataset.

3. **Income Groups**
   - At first, I attempted to divide the data into 4 income groups.
   - After reviewing the referenced website, I aligned with the 7-income group classification.
   - Please note: the grouping logic may differ from the official classification, and thus interpretations might vary.

4. **Correlation Analysis**
   - Due to time constraints, I couldn’t complete correlation analysis between variables, which I originally intended to explore.

5. **Language Barrier**
   - The dataset was entirely in Spanish, which posed a challenge.
   - I tried my best using translation tools and documentation, but some interpretations may be inaccurate.

6. **Request for Re-evaluation**
   - If this submission does not meet expectations, I would be grateful for another opportunity with a different dataset.
   - Ideally, an English-language dataset would be appreciated, though I am ready to tackle any challenge given.

7. **Time Investment**
   - I spent approximately **12 hours** on this task.
   - Due to upcoming midterm exams, I could not dedicate more time, but with additional time, I would have further explored inter-dataset relationships and improved the analysis.

---

## 🔍 Tools & Resources Used

- **Python** (Jupyter Notebook)
- **Libraries**: Pandas, Matplotlib, Seaborn
- **Documentation & Learning Platforms**:
  - Google
  - YouTube
  - ChatGPT
  - W3Schools
  - GeeksforGeeks
  - Official Pandas & Matplotlib docs

---

## 🙏 Final Notes

I understand that this submission was prepared in a short timeframe, and I acknowledge the possibility of misinterpretations. I am committed to learning and growing in this space and genuinely appreciate the opportunity.

Thank you for your time and consideration. I welcome any feedback that can help me improve.

— *Prit Italiya*
