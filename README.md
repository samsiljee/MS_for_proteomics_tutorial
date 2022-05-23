# MS_for_proteomics_tutorial
Repository for a tutorial on analysing MS data in R

## Links
Tutorial on Youtube; https://www.youtube.com/watch?v=GlTRN2jbEa4

Github page; https://lgatto.github.io/RforProteomics/articles/RforProteomics.html

Original article; https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/10.1002/pmic.201400392

Bioconductor; https://www.bioconductor.org/packages/release/data/experiment/vignettes/RforProteomics/inst/doc/RProtVis.html

R for Mass Spec project; https://www.rformassspectrometry.org/

## Notes
MS data can be conceptualised as having various dimensions.
The first dimension is retention time, the time at which the peptides come of the HPLC column.
The second and third dimensions consist of M/Z values, and intensity values - these together form a 2D spectrum, or a MS1 scan.
A subset of this MS1 scan is taken for fragmentation for the MS2 scan. There are varying ways to select for these subsets to optimise time efficiency and coverage.

MS data is formatted as a data table, with one scan per row. The columns cover various values:
1. Index of scan (i.e. first scan, 205th scan...)
2. MS level (MS1, MS2)
3. Retention time
4. Other annotations
5. Matrixes of raw plots, consiting of two values:

a. M/Z values

b. Intensity scores
