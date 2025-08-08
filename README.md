## Welcome to the "*R You out of Memory*" Short Course!

We are so glad you will be joining us!

**Big Data Analytics with R: Arrow and DuckDB**

🗓️ August 8, 2025\
⏰ 1:00pm - 4:30pm\
🏨 Penn 2\
✍️ <https://user2025.r-project.org/>

**Overview**

*Description:* Struggling with datasets that crash R or take forever to process? This hands-on workshop will transform how you handle large data in R! We'll work with a real 9GB dataset (40+ million rows) to learn modern big data tools that scale from your laptop to production systems. You'll master Arrow for lightning-fast file operations, DuckDB for powerful analytics, and discover when to use each tool for maximum efficiency. By the end, you'll confidently process datasets much larger than what traditional R can handle using familiar dplyr syntax.

***Learning goals:***

1.  Understand and practice the "view don't load" mindset using Arrow's lazy evaluation to process data larger than memory.

2.  Apply the 6 core dplyr verbs (`filter()`, `select()`, `arrange()`, `mutate()`, `group_by()`, `summarise()`) and learn strategic `collect()` placement for optimal performance

3.  Practice converting between file formats (CSV ↔ Parquet) and see dramatic speed improvements in action.

4.  Build and execute multi-step analytical pipelines using familiar dplyr syntax that scales to datasets with millions of rows.

5.  Experience DuckDB for complex analytics including joins and window functions on large datasets.

6.  Learn when to choose Arrow vs. DuckDB vs. traditional R for different analytical tasks and data sizes.

    *Target audience:* R users comfortable with basic dplyr operations (`filter()`, `select()`, `group_by()`, `summarise()`) who want to scale their analyses to larger datasets. No prior experience with Arrow or DuckDB required.

**Pre-work**

1.  Please have a recent version of R and RStudio installed.

```         
-    R ≥ 4.2

-    RStudio ≥ 2024.04.1+748
```

2.  Install the following packages

```{{r}}
install.packages(c("usethis", "tidyverse", "arrow", "duckdb", "DBI", "dbplyr", "curl", "glue"))
```

3.  **Critical:** Follow the detailed setup instructions in the provided `pre-workshop_data_download_file.qmd` document to create your project folder and download the 9GB Seattle Library dataset (this takes 8-15 minutes). This step-by-step guide will ensure your workspace is properly configured for the workshop. Github will not allow for this data size as .csv

4.  System requirements: At least 8GB RAM (16GB recommended) and 15GB free disk space for dataset and converted files.

**Instructors:**

[Jeanne McClure, PhD](https://www.linkedin.com/in/jeannemcclure/) is a postdoctoral fellow at NC State University's Data Science and AI Academy and founder of Ars Innovate Technologies and Consulting. She specializes in AI integration, prompt engineering, and workforce development, with a Ph.D. in Learning Design and Technology from NC State. A former NCES fellow and 2025 Posit Cloud Opportunity Grant recipient, she serves on the UNC System AI Pedagogy working group and is a member of RLadies RTP, focusing on expanding access to AI and data science education through hands-on learning and open-source tools.

[Elyse Armstrong](https://www.linkedin.com/in/elysearmstrong/) is a Data Scientist at Common App, where she applies statistical analysis and data science techniques to expand college access and improve equity in the labor market. She holds an M.A. in Education Policy and Analysis from Harvard University and specializes in educational data analytics, helping create more inclusive systems that promote socioeconomic mobility. Elyse is passionate about using R and data science to break down systemic barriers and democratize access to educational and career opportunities.

[Sheila Saia, PhD](https://www.linkedin.com/in/sheilasaia/) (she/her) is an Environmental Data Scientist at Tetra Tech's Center for Ecological Analytics and Modeling (CEAM), where she uses data analytics to predict and minimize human impacts on climate and water resources at regional and national scales. She holds a Ph.D. in Biological and Environmental Engineering from Cornell. She is also the co-organizer of R-Ladies RTP and a member of the R-Ladies Global Team. Sheila is passionate about open science and exploring the relationships between humans, climate, and water resources through data wrangling, modeling, and visualization using R and other analytical tools.

**License and Attribution**

This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). You are free to share and adapt this material for non-commercial purposes with proper attribution.

**Citation:** McClure, J., Armstrong, E., & Saia, S. (2026). *Big data analytics with R: Arrow and DuckDB* [Workshop]. useR! 2025 Conference. Durham, NC

NSF Acknowledgement: This material is based upon work supported by the National Science Foundation under Grant #DGE-2222148. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
