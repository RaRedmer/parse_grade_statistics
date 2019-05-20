# Parse grade statistics
Purpose of this project is the extraction of tables from pdf files obtained from
<a href="https://www.vwlpamt.uni-bonn.de/pruefungsamt/notenstatistiken">official sources</a>
in order to build comprehensive 
grade statistics for multiple semesters. However, the actual extraction process takes the 
respective docx files instead. These were obtained via 
<a href="https://smallpdf.com/de/pdf-in-word">smallpdf</a>. <br>
Further, I proceeded to get meaningful insights from the data like distributions and aggregated 
time series.

**Disclaimer:** This project is **not** finished. The remaining PDFs will also get analysed,
and the docx conversion will be automated.  
There is more to come!


## docx_table_parsing.ipynb
Contains parsing of docx-files and subsequent data cleaning.

## grade_analysis.ipynb
Generates bar and line plots.