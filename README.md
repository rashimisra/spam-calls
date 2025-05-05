# spam-calls

## Project Overview

This project explores over a century of nuisance and fraudulent phone calls in the United States using a comprehensive dataset from the FCC. The analysis focuses on how spam and scam call patterns have evolved over time—highlighting when during the day, month, and year these calls occur most frequently.

The project draws connections between historical trends, consumer behavior, and regulatory responses, including the rise of call-blocking technologies and changes in scammer tactics.

## Objectives

The goal of this project is to:

Identify peak spam hours during the day.

Discover monthly spam patterns by dividing each month into three phases:

Days 1–10

Days 11–20

Days 21–30

Determine the year with the highest volume of spam calls.

Explore long-term trends in spam and fraud activity.

Provide context with policy and enforcement actions by the FCC and FTC.

## Tools & Libraries Used

pandas 

regex (re)

## Key Findings

Peak Hour: Spam calls peak around 10 a.m. local time.

Monthly Trends: Highest activity occurs in the first 10 days of each month, with noticeable dips around the 11th and 20th.

Worst Year: 2018 saw the highest volume of recorded spam calls—around 500,000 in one year.

Behavioral Shift: Scammers are shifting away from calls and now prefer texts and emails.

Demographic Insights: Seniors are among the most call-cautious demographics and have adopted effective spam-screening habits.

## Methodology

Cleaned and processed over 3 million rows of call record data.

Parsed timestamps to extract hourly and monthly windows.

Categorized each date into three phases per month.

Grouped and counted call occurrences by time units (hour, day-range, year).

Used regular expressions to match patterns and classify call types if applicable.


