# Academic Radiology Percentile Calculators

A collection of web-based percentile calculators for comparing academic productivity metrics across radiology subspecialties.

## Overview

These calculators allow academic radiologists to compare their publication metrics against peers in their subspecialty. Each calculator includes data from faculty at major academic medical centers across the United States.

## Available Calculators

### Body Imaging Subspecialties (NEW - December 2024)

| Subspecialty | Faculty | Institutions | Color Theme | File |
|-------------|---------|--------------|-------------|------|
| **Cardiothoracic Imaging** | 587 | 84 | Lime Green | `Cardiothoracic_Imaging_Percentile_Calculator.html` |
| **Abdominal Imaging** | 1,451 | 102 | Magenta | `Abdominal_Imaging_Percentile_Calculator.html` |

### Other Subspecialties

| Subspecialty | Faculty | Institutions | Color Theme | File |
|-------------|---------|--------------|-------------|------|
| Neuroradiology | 1,057 | ~100 | Purple | `Neuroradiology_Percentile_Calculator.html` |
| Musculoskeletal Radiology | 673 | ~100 | Green | `MSK_Radiology_Percentile_Calculator.html` |
| Breast Imaging | 509 | ~100 | Pink | `Breast_Imaging_Percentile_Calculator.html` |
| Nuclear Medicine | 522 | ~100 | Brown | `Nuclear_Medicine_Percentile_Calculator.html` |
| Interventional Radiology | 847 | 102 | Red | `Interventional_Radiology_Percentile_Calculator.html` |
| Pediatric Radiology | 986 | ~100 | Cyan | `Pediatric_Radiology_Percentile_Calculator.html` |

## Features

### Two Operating Modes

1. **Enter Metrics Tab**: Manually input a metric value to see your percentile ranking
2. **Find by Name Tab**: Look up a specific faculty member to see all their percentile rankings

### Metrics Available

- **Total Citations** - Sum of all citations received
- **Total Papers** - Total number of publications
- **H-Index** - Hirsch index (h papers with at least h citations each)
- **First Author Papers** - Publications as first author
- **First Author Citations** - Citations from first-author publications
- **Last Author Papers** - Publications as last/senior author
- **Last Author Citations** - Citations from last-author publications
- **RY Metric** ⭐ - Weighted metric emphasizing leadership roles (highlighted in gold)

### Filter Options

- **Rank**: All, Assistant Professor, Associate Professor, Professor
- **Sex**: All, Male, Female
- **Years Since First Publication**: 0-5, 6-10, 11-15, 16-20, 21-25, 26-30, 31-35, 36-40, >40 years

## RY Metric

The RY Metric (formerly Yousem Metric) is a novel bibliometric measure that weights first and last authorship positions 5× more heavily than middle authorship to distinguish research leaders from collaborative contributors.

**Formula:**
```
RY Metric = (First+Last author citations × 5) + (Middle author citations) 
          + 10 × [(First+Last author papers × 5) + (Middle author papers)]
```

This metric recognizes that first and last author positions typically indicate greater intellectual contribution and leadership in academic publishing.

## Data Sources

- Publication data sourced from **Scopus** via the Elsevier API
- H-Index collected via Scopus Author Retrieval API
- Faculty information gathered from institutional websites
- Data current as of December 2024

## Technical Details

### File Structure

```
/
├── index.html                                    # Main landing page with links to all calculators
├── README.md                                     # This documentation file
├── Cardiothoracic_Imaging_Percentile_Calculator.html
├── Abdominal_Imaging_Percentile_Calculator.html
├── Neuroradiology_Percentile_Calculator.html
├── MSK_Radiology_Percentile_Calculator.html
├── Breast_Imaging_Percentile_Calculator.html
├── Nuclear_Medicine_Percentile_Calculator.html
├── Interventional_Radiology_Percentile_Calculator.html
└── Pediatric_Radiology_Percentile_Calculator.html
```

### Technology Stack

- Pure HTML/CSS/JavaScript (no frameworks required)
- Google Fonts (DM Sans, DM Serif Display)
- Responsive design for mobile and desktop
- Self-contained files (data embedded in each HTML file)

### Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Usage

### GitHub Pages Deployment

1. Upload all HTML files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Access via `https://[username].github.io/[repository]/`

### Local Usage

Simply open any HTML file directly in a web browser. No server required.

## Color Scheme Summary

| Subspecialty | Primary Color | Hex Code |
|-------------|---------------|----------|
| Neuroradiology | Purple | #7c3aed |
| MSK Radiology | Green | #059669 |
| Breast Imaging | Pink | #db2777 |
| Nuclear Medicine | Brown | #b45309 |
| Interventional Radiology | Red | #991b1b |
| Pediatric Radiology | Cyan | #0891b2 |
| Cardiothoracic Imaging | Lime Green | #65a30d |
| Abdominal Imaging | Magenta | #c026d3 |

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

## Contact

David M. Yousem, MD, MBA  
Johns Hopkins University School of Medicine  
Email: dyousem1@jhu.edu

## Version History

- **December 2024**: Added Cardiothoracic Imaging (587 faculty) and Abdominal Imaging (1,451 faculty) calculators
- **November 2024**: Added Interventional Radiology (847 faculty) and Pediatric Radiology (986 faculty) calculators
- **October 2024**: Added Nuclear Medicine (522 faculty) calculator
- **September 2024**: Added Breast Imaging (509 faculty) calculator
- **August 2024**: Added MSK Radiology (673 faculty) calculator
- **July 2024**: Initial release with Neuroradiology (1,057 faculty) calculator

## License

For academic and research purposes only. Please cite appropriately if used in publications.
