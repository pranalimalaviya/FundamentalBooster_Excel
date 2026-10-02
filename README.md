# Fundamental Booster — Excel Project

Welcome to the **Fundamental Booster Excel Project**

This project is a comprehensive Excel workbook designed to practice and demonstrate **spreadsheet modeling, data organization, logical evaluations, 
lookup functions, statistical analysis, and dynamic date calculations**.
The project focuses on building strong Excel fundamentals while applying them to practical datasets such as **student grades, sales transactions, 
and employee records**.

## Project Overview

The main objective of this project is to build core **Excel and data analysis skills** by organizing information across multiple specialized worksheets 
and applying a variety of Excel functions.

### Learning Objectives

This project demonstrates proficiency in:

* Lookup and Reference Functions
* Logical and Conditional Functions
* Mathematical and Statistical Functions
* Date and Time Calculations
* Data Organization and Management
* Summary and Analytical Calculations
* Formula-Based Data Validation
  
# Workbook Structure

The workbook contains the following major worksheets:

## 1.Project Instructions

### Purpose

Acts as the **master guideline sheet** for the entire workbook.

### Content

* Project requirements
* Module objectives
* Instructions for each worksheet
* Formula requirements
* Validation rules
* Expected Excel functions

This sheet provides the overall structure and instructions for completing the project.

## 2. Students Grade

### Purpose

Manages student academic records, grades, and performance evaluation.

### Features

* Student information
* Mathematics scores
* Science scores
* English scores
* Enrollment dates
* Total and average scores
* Letter grade evaluation
* High Achiever identification
* Discount eligibility
* Summary calculations

### Functions Used

IF
IFS
AND
OR
COUNTA
COUNTIF
AVERAGE

### Example Logic

**High Achiever**

Checks whether a student satisfies multiple performance conditions using the `AND()` function.

**Discount Eligible**

Checks whether a student satisfies at least one qualifying condition using the `OR()` function.

## 3. Sales Data

### Purpose

Tracks sales transactions and analyzes regional and financial performance.

### Features

* Sales ID
* Product
* Region
* Salesperson
* Sales Amount
* Sales Date
* Discount Tier
* Region Status
* Summary and analysis section

### Lookup Functions

The worksheet demonstrates multiple lookup techniques:

VLOOKUP
INDEX
MATCH
XMATCH

### Aggregation Functions

SUM
SUMIF
AVERAGE
AVERAGEIF

These functions are used to summarize sales data and calculate metrics based on specific conditions.

## 4.Employee Data

### Purpose

Manages employee information, salaries, departments, and employment timelines.

### Features

* Employee ID
* Employee Name
* Department
* Salary
* Joining Date
* Employee Tenure

### Date Functions

The worksheet uses dynamic date calculations such as:

DATEDIF
TODAY
YEAR

For example:

=DATEDIF(E2,TODAY(),"Y")

This formula calculates the number of completed years since an employee's joining date.

Because `TODAY()` automatically updates with the current date, the tenure calculation remains dynamic.

# Excel Functions Used

The project covers a wide range of Excel functions.

| Category                     | Functions                                                   |
| ---------------------------- | ----------------------------------------------------------- |
|  Lookup & Reference        | `VLOOKUP`, `INDEX`, `MATCH`, `XMATCH`                       |
|  Logical & Conditional     | `IF`, `IFS`, `AND`, `OR`                                    |
|  Statistical & Aggregation | `SUM`, `SUMIF`, `AVERAGE`, `AVERAGEIF`, `COUNTA`, `COUNTIF` |
|  Date & Time               | `DATEDIF`, `TODAY`, `YEAR`                                  |


# Skills Demonstrated

This project demonstrates practical knowledge of:

* Excel formulas
* Data organization
* Conditional logic
* Lookup operations
* Data summarization
* Statistical calculations
* Date calculations
* Spreadsheet modeling
* Basic data analysis

# Project Outcome

After completing this project, the following Excel concepts are practiced:

**Data → Formula → Analysis → Summary**

The workbook provides hands-on practice with both **fundamental and advanced Excel operations** that are useful 
for data analysis and spreadsheet-based projects.

## Project Highlights

* Multiple structured datasets
* Practical Excel formulas
* Multiple lookup techniques
* Logical decision-making
* Statistical analysis
* Dynamic date calculations
* Organized summary sections
* Practical business and academic datasets
