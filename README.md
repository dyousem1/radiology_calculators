# Academic Radiology Percentile Calculators

A collection of web-based percentile calculators for comparing academic productivity metrics across radiology subspecialties.

## Overview

These calculators allow academic radiologists to compare their publication metrics against peers in their subspecialty. Each calculator includes data from faculty at major academic medical centers across the United States.

## Available Calculators

| Subspecialty | Faculty | Institutions | Color Theme | File |
|-------------|---------|--------------|-------------|------|
| Abdominal Imaging | 1,451 | 102 | Magenta | `Abdominal_Imaging_Percentile_Calculator.html` |
| Body Imaging Combined | 2,038 | 103 | Navy Blue | `Body_Imaging_Combined_Percentile_Calculator.html` |
| Breast Imaging | 969 | 99 | Pink | `Breast_Imaging_Percentile_Calculator.html` |
| Cardiothoracic Imaging | 587 | 84 | Lime Green | `Cardiothoracic_Imaging_Percentile_Calculator.html` |
| Interventional Neuroradiology | 347 | 101 | Orange | `Neurointerventional_Radiology_Percentile_Calculator.html` |
| Interventional Radiology | 847 | 99 | Red | `Interventional_Radiology_Percentile_Calculator.html` |
| MSK Radiology | 679 | 99 | Green | `MSK_Percentile_Calculator.html` |
| Neuroradiology | 1,200+ | 100+ | Purple | `Neuroradiology_Percentile_Calculator.html` |
| Nuclear Medicine | 522 | 95 | Brown | `Nuclear_Medicine_Percentile_Calculator.html` |
| Pediatric Radiology | 986 | 98 | Cyan | `Pediatric_Radiology_Percentile_Calculator.html` |

**Note:** Body Imaging Combined includes all faculty from both Abdominal Imaging and Cardiothoracic Imaging.

**Note:** Interventional Neuroradiology (INR) is distinct from Interventional Radiology (IR). INR includes neuroradiologists, neurosurgeons, and neurologists who perform neurointerventional procedures.

## Features

### Dual-Tab Interface
- **Enter Your Metrics:** Input your values to calculate your percentile ranking
- **Find by Name:** Search for any faculty member to view their complete metrics

### Filtering Options
- Filter by academic rank (Assistant, Associate, Full Professor)
- Filter by sex (Male, Female)
- Filter by academic age (years since first publication)

### Metrics Included
- **Total Publications** - All indexed publications
- **First Author Publications** - Papers where faculty is first author
- **Last Author Publications** - Papers where faculty is senior/corresponding author
- **Middle Author Publications** - Collaborative papers
- **Total Citations** - Sum of all citations
- **H-Index** - Hirsch index measuring productivity and impact
- **RY Metric** - Weighted metric emphasizing first/last authorship (5× weight vs 1× for middle)

## The RY Metric

The RY Metric (formerly Yousem Metric) is a bibliometric measure that emphasizes leadership roles in academic publishing:

```
RY Metric = Weighted Citations + (10 × Weighted Papers)

Where:
- First/Last author positions: 5× weight
- Middle author positions: 1× weight
```

This metric rewards researchers who lead projects (first author) or supervise them (last/senior author), providing a more nuanced view of academic contribution than simple publication or citation counts.

## Data Source

All bibliometric data were derived from Scopus searches conducted between November 2025 and January 2026. Faculty information was gathered from academic institution websites and verified against Scopus author profiles.

## Usage

### Online Access
Visit the [main hub page](https://dyousem1.github.io/radiology_calculators/) to access all calculators.

### How to Use
1. Select your subspecialty
2. **Enter Metrics Tab:** Input your values to see your percentile
3. **Find by Name Tab:** Search for any faculty member in the database

## Academic Age Bins

Faculty are grouped by years since first publication:
- 0-5 years (Early career)
- 6-10 years
- 11-15 years
- 16-20 years
- 21-25 years
- 26-30 years
- 31-35 years
- 36-40 years
- >40 years (Senior faculty)

## Limitations

- Data reflects Scopus indexing; some publications may not be captured
- Academic rank information may be incomplete for some institutions
- H-index values are point-in-time snapshots
- Some faculty may have incomplete or missing Scopus profiles

## Version History

- **January 2026**: Added Interventional Neuroradiology (347 faculty) calculator
- **December 2025**: Added Breast Imaging (969 faculty), Cardiothoracic Imaging (587 faculty), Abdominal Imaging (1,451 faculty), and Body Imaging Combined (2,038 faculty) calculators
- **November 2025**: Added Interventional Radiology (847 faculty) and Pediatric Radiology (986 faculty) calculators
- **October 2025**: Added Nuclear Medicine (522 faculty) calculator
- **September 2025**: Added MSK Radiology (679 faculty) calculator
- **August 2025**: Initial release with Neuroradiology (1,200+ faculty) calculator

## License

© 2025-2026 David M. Yousem, MD, MBA

For academic and research purposes only. Please cite appropriately if used in publications.

## Contact

For questions or feedback, please contact:

**David M. Yousem, MD, MBA**  
Johns Hopkins University School of Medicine  
Email: dyousem1@jhu.edu
