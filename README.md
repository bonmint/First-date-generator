# First Review Generator V1.0
This tool will help you automatically extract the exact date of the first review of an Asin.

## What you need:
A *.xlsx file with only one column in it: [asin]   
**Caution: _asin_ should be written in lower case.**

## Usage:
- Step1: Select the asin_file from your computer with file browser
- Step2: Click the **[Generate]** button, which will generate a file named 'last_review_url.csv'
- Step3: Select the file generated above with file browser
- Step4: Click **[Get Date]** button, which will generate a file named 'date_with_url.csv'
- Step5: All done, now it's ctrl+c, ctrl+v time! Go and grab yourself a cup of bubble tea:)

## Notes:
Given that reviews over 500 pages on Amazon are inaccessible, the earliest date of an asin whose review page number exceeds 500 is not credible, please filter out them by the column ['number'] and exclude them from your analysis, although it is not possible to get the correct date manually as well.
