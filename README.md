# Military Spending Visualization Deconstruction & Reconstruction  

This project critiques and reconstructs a visualization of the **Top 15 Military Spenders in 2022**, originally published by the Stockholm International Peace Research Institute (SIPRI). The work was completed as part of the *Data Visualisation & Communication* coursework.  

## Project Overview  
The original visualization, presented as a treemap, suffered from issues in clarity, design, and accuracy. This project applies a **deconstruction–reconstruction approach** to identify those issues and build an improved chart using **R and ggplot2**.  

### Key Steps  
- **Deconstruction**:  
  - The treemap was unsuitable for ranking comparisons.  
  - Uniform green coloring reduced readability.  
  - Displayed values did not align with the source data.  

- **Reconstruction**:  
  - Designed a **horizontal bar chart** for better comparison.  
  - Applied a gradient color scheme to highlight expenditure levels.  
  - Corrected discrepancies using the SIPRI Military Expenditure Database.  

## Tools & Methods  
- **Language**: R  
- **Libraries**: `ggplot2`, `readxl`  
- **Data Source**: [SIPRI Military Expenditure Database](https://www.sipri.org/databases/milex)  
- **Deliverables**: RMarkdown report, PDF summary, visualization outputs  
