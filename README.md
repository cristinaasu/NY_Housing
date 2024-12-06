# Analysis of NY Housing Price Determinants 
This project investigates the determinants of housing prices in New York State by analyzing property characteristics, public school quality, and socioeconomic factors. The study is conducted using data from various sources and employs econometric methods to build models that explain housing price variability.

# Replication Package

- **Income.dta**: Contains data on income levels for ZIP codes in New York State.
- **NY_Housing.dta**: The primary dataset used for analysis, containing property-level data merged with educational and socioeconomic variables.
- **NY_Housing.do**: Stata `.do` file used for data preprocessing, cleaning, and regression analysis.
- **NY_Housing.pdf**: The final report detailing the research findings, methodologies, and conclusions.
- **public_school_ny.dta**: Data on public schools in New York, including metrics such as student-teacher ratios and school density.
- **~NY_Housing.do.stswp**: Temporary or backup file generated during Stata analysis.

# How to Use

1. **Data Preparation**:
   - Load `NY_Housing.dta` and other `.dta` files in Stata.
   - Run `NY_Housing.do` to replicate the analysis and generate results.

2. **Reproducing the Report**:
   - Compile the LaTeX project to produce `NY_Housing.pdf`.
   - Ensure all dependencies, including the referenced `.tex` files and figures, are in place.

3. **Replication**:
   - The Stata `.do` file contains step-by-step commands to replicate the data preprocessing, cleaning, and regression analysis.

# Acknowledgments

This project was conducted as part of ECO375: Applied Econometrics at the University of Toronto. We acknowledge the support of the Department of Economics and the course instructor.
