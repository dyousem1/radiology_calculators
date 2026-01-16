# Academic Radiology Bibliometric Tools

Percentile calculators and institutional rankings for academic radiology faculty scholarship across ten subspecialties.

**Created by David M. Yousem, MD, MBA — Johns Hopkins University**

🔗 **Live Site:** [https://dyousem1.github.io/radiology_calculators/](https://dyousem1.github.io/radiology_calculators/)

---

## Overview

This repository provides free, web-based tools for benchmarking academic productivity in radiology. All data is sourced from Scopus and includes publication counts, citation metrics, and H-indices for over 7,200 faculty across 124 academic institutions.

---

## 🏛️ Institutional Ranking Tools (NEW)

Compare academic institutions across multiple bibliometric metrics:

| Tool | Description |
|------|-------------|
| **[Institution Rankings Lookup](https://dyousem1.github.io/radiology_calculators/Institution_Rankings_Lookup.html)** | Search for any institution and view its rankings across all ten subspecialties. Filter by total papers, citations, papers per faculty, mean H-index, or median H-index. |
| **[Top 25 Institutions by Subspecialty](https://dyousem1.github.io/radiology_calculators/Top_25_Institutions_by_Subspecialty.html)** | View the leading 25 institutions in each subspecialty, ranked by your choice of metric. Compare productivity across all metrics simultaneously. |

---

## 📊 Individual Percentile Calculators

Calculate where you rank among academic radiology faculty by subspecialty, academic rank, sex, and years in practice:

| Subspecialty | Faculty | Institutions | Calculator |
|--------------|---------|--------------|------------|
| Neuroradiology | 1,057 | 100 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Neuroradiology_Percentile_Calculator.html) |
| Neurointerventional Radiology | 333 | 128 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Neurointerventional_Radiology_Percentile_Calculator.html) |
| Musculoskeletal Radiology | 673 | 93 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/MSK_Percentile_Calculator.html) |
| Breast Imaging | 969 | 107 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Breast_Imaging_Percentile_Calculator.html) |
| Nuclear Medicine | 522 | 108 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Nuclear_Medicine_Percentile_Calculator.html) |
| Interventional Radiology | 847 | 102 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Interventional_Radiology_Percentile_Calculator.html) |
| Pediatric Radiology | 527 | 91 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Pediatric_Radiology_Percentile_Calculator.html) |
| Abdominal Imaging | 885 | 103 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Abdominal_Imaging_Percentile_Calculator.html) |
| Cardiothoracic Imaging | 591 | 86 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Cardiothoracic_Imaging_Percentile_Calculator.html) |
| Body Imaging Combined | 2,445 | 102 | [Open Calculator](https://dyousem1.github.io/radiology_calculators/Body_Imaging_Combined_Percentile_Calculator.html) |

---

## Metrics Included

**Individual Calculators:**
- Total publications
- Total citations
- H-index
- First/last author publications
- Middle author publications
- RY Metric (first/last authorship weighted 5× middle authorship)

**Institutional Rankings:**
- Total papers
- Total citations
- Papers per faculty
- Mean H-index
- Median H-index

---

## How to Use

### Individual Calculators
1. Select a subspecialty calculator
2. Choose filters (academic rank, sex, years in practice range)
3. Enter your metrics (publications, citations, H-index, etc.)
4. View your percentile ranking within the filtered cohort

### Institutional Lookup
1. Select an institution from the dropdown
2. Choose a ranking metric
3. View the institution's rank across all subspecialties where faculty are present

### Top 25 Rankings
1. Select a subspecialty
2. Choose a ranking metric (or view all metrics)
3. See the top 25 institutions with faculty counts and metric values

---

## Data Sources & Methodology

- **Source:** Scopus database
- **Faculty identification:** Web scraping of institutional faculty directories
- **Rank verification:** SerpAPI and institutional website searches
- **First publication year:** Scopus Search API with date sorting
- **H-index:** Selenium-based collection from Scopus author profiles

**RY Metric Formula:**
```
RY Metric = (First Author Pubs × 5) + (Last Author Pubs × 5) + Middle Author Pubs
```

---

## Files in Repository

```
radiology_calculators/
├── index.html                                    # Main landing page
├── README.md                                     # This file
├── Institution_Rankings_Lookup.html              # Institution search tool
├── Top_25_Institutions_by_Subspecialty.html      # Top 25 rankings
├── Neuroradiology_Percentile_Calculator.html
├── Neurointerventional_Radiology_Percentile_Calculator.html
├── MSK_Percentile_Calculator.html
├── Breast_Imaging_Percentile_Calculator.html
├── Nuclear_Medicine_Percentile_Calculator.html
├── Interventional_Radiology_Percentile_Calculator.html
├── Pediatric_Radiology_Percentile_Calculator.html
├── Abdominal_Imaging_Percentile_Calculator.html
├── Cardiothoracic_Imaging_Percentile_Calculator.html
└── Body_Imaging_Combined_Percentile_Calculator.html
```

---

## Contact

David M. Yousem, MD, MBA  
Professor of Radiology  
Johns Hopkins University School of Medicine  
📧 dyousem1@jhu.edu

---

## License

This project is provided for educational and research purposes. Data is sourced from publicly available Scopus records.

---

*Last updated: January 2025*
