# First Review Generator V1.0
This tool will help you automatically extract the exact date of the first review.

## What you need:
A *.xlsx file with two columns in it: ['href] and ['number]

- **['href']** refers to the url of detailed page of an ASIN. 
Here is an example:
https://www.amazon.com/Logitech-MK270-Wireless-Keyboard-Mouse/dp/B079JLY5M5/ref=lp_16225007011_1_3?th=1

Noted: your url must be formatted or similarly formatted(not sure) as shown above.

- **['number']** refers to the number of global reviews. 

## Usage:
- Step1: Select the file from your computer with file browser
- Step2: Click the [Generate] button, which will generate a file named 'last_review_url.csv'
- Step3: Select the file generated above with file browser
- Step4: Click [Get Date], which will generate a file named 'date_with_url.csv'
- Step5: All done, now it's ctrl+c, ctrl+v time! Go and grab yourself a cup of bubble tea:)
