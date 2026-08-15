# Radiology Percentile Calculators

**Academic Productivity Benchmarking by Subspecialty**

David M. Yousem, MD, MBA | Johns Hopkins University School of Medicine

---

## Overview

Compare your scholarly metrics against peers in your radiology subspecialty. Each calculator provides percentile rankings based on comprehensive Scopus bibliometric data, with filtering by academic rank, sex, and years since first publication.

🔗 **Live Site:** [https://dyousem1.github.io/radiology_calculators/](https://dyousem1.github.io/radiology_calculators/)

---

## Data Currency & Update Schedule

### Last Scopus Data Pull by Subspecialty

| Subspecialty | Last Scopus Pull | Faculty | Institutions |
|---|---|---|---|
| Abdominal Imaging | August 14, 2026 | 1,342 | 105 |
| All Radiologists | August 14, 2026 | 7,345 | 179 |
| Body Imaging Combined | August 14, 2026 | 1,894 | 106 |
| Breast Imaging | August 14, 2026 | 876 | 111 |
| Cardiothoracic Imaging | August 14, 2026 | 553 | 87 |
| Emergency Radiology | August 14, 2026 | 421 | 66 |
| Interventional Radiology | August 14, 2026 | 880 | 104 |
| MSK Radiology | August 14, 2026 | 618 | 94 |
| Neurointerventional Radiology | August 14, 2026 | 423 | 135 |
| Neuroradiology | August 14, 2026 | 1,037 | 121 |
| Nuclear Medicine | August 14, 2026 | 655 | 115 |
| Pediatric Radiology | August 14, 2026 | 930 | 112 |

### Update Commitments

- **Bibliometric values** (citations, publications, H-index): Refreshed from Scopus approximately every **4 months**
- **Faculty roster** (additions of new hires, removals of retired/departed faculty): Reviewed and updated **annually each August**, requiring manual verification across 184 institutions

### Data Accuracy

Bibliometric data are sourced exclusively from **Scopus**. Overall accuracy is estimated at **90–95%**. Discrepancies may arise from author name disambiguation, duplicate Scopus profiles, or publications indexed only in other databases (e.g., Google Scholar, Web of Science). To report an error, contact [dyousem1@jhu.edu](mailto:dyousem1@jhu.edu).

---

## Available Calculators

| Subspecialty | Faculty | Institutions | Status |
|--------------|---------|--------------|--------|
| 🫁 Abdominal Imaging | 1,342 | 105 | ✅ Live |
| 📊 All Radiologists | 7,345 | 179 | ✅ Live |
| 🫀 Body Imaging Combined | 1,894 | 106 | ✅ Live |
| 🎗️ Breast Imaging | 876 | 111 | ✅ Live |
| ❤️ Cardiothoracic Imaging | 553 | 87 | ✅ Live |
| 🚨 Emergency Radiology | 421 | 66 | ✅ Live |
| 🩺 Interventional Radiology | 880 | 104 | ✅ Live |
| 🦴 MSK Radiology | 618 | 94 | ✅ Live |
| 🔬 Neurointerventional Radiology | 423 | 135 | ✅ Live |
| 🧠 Neuroradiology | 1,037 | 121 | ✅ Live |
| ☢️ Nuclear Medicine | 655 | 115 | ✅ Live |
| 👶 Pediatric Radiology | 930 | 112 | ✅ Live |

**Total: 7,728 subspecialty listings across 181 Institutions** (7,345 unique individuals in the deduplicated All Radiologists calculator)

---

## Analysis Tools

### 🏥 Institution Rankings Lookup

Compare any institution's rankings across all subspecialties with 5 different metrics:
- Total Papers
- Total Citations
- Papers Per Faculty
- Mean H-Index
- Median H-Index

**Includes NIH Radiology Funding (BRIMR 2025)** showing departmental NIH grant totals for 66 funded departments.

**Includes Overall** view showing aggregated metrics across all subspecialties for each institution.

### 🏆 Top 25 Institutions by Subspecialty

View the top 25 ranked institutions for each subspecialty across all metrics. 

**Includes Overall** tab showing combined rankings across all subspecialties:
- 179 institutions aggregated from all subspecialties
- 7,345 unique faculty
- Mayo Clinic separated by campus (Rochester, Jacksonville, Phoenix)

**Includes NIH Funding (BRIMR 2025)** tab ranking departments by NIH grant funding.

---

## Metrics Included

Each calculator provides percentile rankings for:

- **Total Citations**
- **Total Papers**
- **H-Index**
- **First Author Papers**
- **First Author Citations**
- **Last Author Papers**
- **Last Author Citations**
- **RY Metric** ⭐

---

## The RY Metric

A novel bibliometric measure that weights first and last authorship 5× more than middle authorship, distinguishing research leaders from collaborative contributors.

### Formula

\`\`\`
RY Metric = Weighted Citations + (10 × Weighted Publications)
\`\`\`

Where:
- **First/Last author contributions** are weighted **5×**
- **Middle author contributions** are weighted **1×**

### Why RY Metric?

Traditional metrics like H-index and total citations don't distinguish between leadership roles (first/last author) and collaborative contributions (middle author). The RY Metric addresses this by rewarding those who lead research projects.

---

## Filtering Options

All calculators support filtering by:

- **Academic Rank:** Assistant Professor, Associate Professor, Professor
- **Sex:** Male, Female
- **Years Since First Publication:** 1-5, 6-10, 11-15, 16-20, 21-25, 26-30, 31-35, 36-40, >40 years
- **Academic Track:** Research/Tenure track, Clinical track *(available in All Radiologists calculator)*

---

## Data Source

All bibliometric data is sourced from the **Scopus** database, including:
- Publication counts and citation metrics
- Authorship position analysis
- H-index values
- First publication year

Institution names harmonized to 179 institutions (Mayo Clinic separated into 3 campuses: Rochester, Jacksonville, Phoenix).

---

## Recent Updates (August 2026)

- **August 14, 2026 Data Refresh (master 8.8.5):** 11 calculators and the Top 25 Institutions tool repopulated from the August 14, 2026 Scopus pull. All 12 calculators, the Institution Rankings Lookup, and the Top 25 Institutions tool are on the August 14, 2026 data.
- **H-Index basis changed:** H-index values are now computed from each author's Scopus-indexed document set (pooled across merged author profiles) rather than taken from the Scopus profile page. Values differ from profile-page h-indices for faculty with merged profiles.
- **Neurointerventional Radiology cohort expanded** to the full 2026 neurointerventional cohort (423 practitioners), including neurosurgery- and neurology-trained neurointerventionalists.
- **RY Metric corrected** in all calculators to Weighted Citations + (10 × Weighted Publications); previous calculator versions displayed weighted publications only.

## Recent Updates (May 2026)

- **May 2026 Data Refresh (v8.1):** 11 subspecialty calculators updated from Scopus master file v8.1 (May 2, 2026). Nuclear Medicine pending separate corrections.
- **Sex/Subspecialty Corrections:** Wilson David, Brandon David, Sohn Jae, Baker Amanda, and Dawn Wilson records corrected following Scopus author-ID verification.
- **Harvard Affiliate Cleanup:** 47 misattributions corrected across MGH, BWH, BIDMC, and other Harvard-affiliated institutions.
- **Foreign/Non-Academic Cleanup:** 13 faculty records removed (foreign institutions, private practice, non-academic).
- **All Radiologists Calculator:** Now includes 7,035 unique faculty from 165 institutions (deduplicated from master Tab 1).
- **Institution Rankings Lookup:** Now covers 179 unique institutions across 12 subspecialty views.
- **Mayo Clinic split:** Continues to be tracked by campus (Rochester, Jacksonville, Phoenix).
- **NIH Funding:** BRIMR 2025 data unchanged — 66 funded departments.

---

## Usage

1. Visit the [main hub page](https://dyousem1.github.io/radiology_calculators/)
2. Select your subspecialty
3. **Enter Metrics Tab:** Input your values to see your percentile
4. **Find by Name Tab:** Search for any faculty member in the database
5. **Institution Rankings:** Compare institutions across subspecialties (includes Overall)
6. **Top 25 Institutions:** View rankings by subspecialty (includes Overall)

---

## Files

| Calculator | Filename |
|------------|----------|
| Abdominal Imaging | \`Abdominal_Imaging_Percentile_Calculator.html\` |
| All Radiologists | \`All_Radiologists_Percentile_Calculator.html\` |
| Body Imaging Combined | \`Body_Imaging_Combined_Percentile_Calculator.html\` |
| Breast Imaging | \`Breast_Imaging_Percentile_Calculator.html\` |
| Cardiothoracic Imaging | \`Cardiothoracic_Imaging_Percentile_Calculator.html\` |
| Emergency Radiology | `Emergency_Radiology_Percentile_Calculator.html` |
| Interventional Radiology | \`Interventional_Radiology_Percentile_Calculator.html\` |
| MSK Radiology | \`MSK_Percentile_Calculator.html\` |
| Neurointerventional Radiology | \`Neurointerventional_Radiology_Percentile_Calculator.html\` |
| Neuroradiology | \`Neuroradiology_Percentile_Calculator.html\` |
| Nuclear Medicine | \`Nuclear_Medicine_Percentile_Calculator.html\` |
| Pediatric Radiology | \`Pediatric_Radiology_Percentile_Calculator.html\` |
| Institution Rankings | \`Institution_Rankings_Lookup.html\` |
| Top 25 Institutions | \`Top_25_Institutions_by_Subspecialty.html\` |

---

## License

© 2026 David M. Yousem, MD, MBA

---

## Contact & Corrections

For questions, feedback, or data corrections:

- **David M. Yousem, MD, MBA**
- Johns Hopkins University School of Medicine
- 📧 [dyousem1@jhu.edu](mailto:dyousem1@jhu.edu)

**To report a missing faculty member, incorrect data, or name/institution error**, use the **Submit a Correction** button on the [main site](https://dyousem1.github.io/radiology_calculators/) or email directly. Corrections are reviewed manually and applied at the next scheduled data refresh.
