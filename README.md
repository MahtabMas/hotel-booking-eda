# Hotel Booking Dataset — Step 1: Exploratory Data Analysis (EDA)

## Overview

This project begins an exploratory analysis of a small hotel booking dataset (195 rows × 4 columns). 

The goal for the first step is to load, scan, and summarize the raw data.

## Dataset

File: hotel-booking-data.txt 

Columns:['Date', 'Company', 'Person Name', 'Room number']

 'Date': currently stored as string

 'Company': categorical

 'Person Name': categorical

 'Room number': numeric,



## Steps Completed

1. Loaded dataset with Pandas

2. Quick scan: shape, columns, head, tail, and random rows.

3. General info: data types, non-null counts, memory usage.

4. Descriptive statistics:

    Numeric (Room number) summary.

    Categorical (date,Company, Person Name) summary.

5. Missing values check.

6. Check unique values

7. First simple plots:

    Top 10 companies by counts.

    Distribution of room numbers.

## Key Observations

Dataset has 195 rows and 4 columns.

Missing values: Date: 0, Person Name: 42, Room number: 42, Company: 61

Date is stored as object/string (not datetime).

Room number is numeric, but should be treated as categorical.

Company column has multiple unique values, with a few frequent ones dominating.
