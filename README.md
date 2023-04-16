My template for automatically generating APA tables in R. Builds on the capabilities of `flextable` and `officer`. A flexible alternative to `nice_table` which does something very similar, but allows me to customize things more easily. 

Need to include function to optionally label the p-value column with significance stars automatically.

Best to use this script alongside a separate CSV file that contains the path and parameters for each table (e.g., whether footnote is present, a column containing the footnote if it is present) to fully automate table production for a project.
