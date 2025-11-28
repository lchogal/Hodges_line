# Hodges Family Tree

Interactive family tree visualization for the Hodges lineage.

## View

https://lchogal.github.io/Hodges_line/

## About

Created by [Leslie Hodges Gallagher](https://lchogal.github.io/cv/), granddaughter of Chauncey William Hodges (1910-1977).

Research compiled from Geni.com, FamilySearch.org, and FindAGrave.com. This is a working draft - primary sources are still being verified.

## Requirements

To regenerate the family tree visualizations:

- Python 3.11.5+
- pandas
- Graphviz 14.0.4+
- Quarto 1.3+ (for webpage rendering)

Install dependencies:
```bash
pip install pandas
brew install graphviz quarto
```

## Files

- `index.html` - Interactive family tree webpage
- `data/Hodges_line.csv` - Genealogy data
- `convert_family.py` - Python script to generate tree visualizations
- `output/` - Generated tree files (PNG, SVG, HTML)

## Contact

Questions or corrections: [hodges.gallagher@gmail.com](mailto:hodges.gallagher@gmail.com)
