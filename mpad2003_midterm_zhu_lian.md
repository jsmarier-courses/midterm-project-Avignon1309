November 1st 2024
MPAD 2003 - Introductory Data Storytelling
Zhu Lian
Presented to Jean-Sébastien Marier

# Midterm Project: Exploratory Data Analysis (EDA)



## Foreword

In this assignment, I will analyze data extracted from the "2024 Service Requests dataset", an intriguing set of information with plenty to uncover.

## 1. Introduction

This assignment explores a City of Ottawa dataset, accessible on the Open Ottawa portal, to analyze the resolution status of various service requests. Covering issues such as city infrastructure and public transit, the dataset includes 11 fields, from Service Request ID and Status to Channel and Description, with both numerical (e.g., dates) and categorical (e.g., issue types) data. I imported the dataset into Google Sheets for a clearer format, making it easier to explore the relationships and trends within each category.

The original dataset is accessible here: https://open.ottawa.ca/documents/65fe42e2502d442b8a774fd3d954cac5/about, on Open Ottawa, with my cleaned CSV version available on GitHub: https://github.com/jsmarier-courses/midterm-project-Avignon1309/blob/main/Midterm_dataset.csv.

This assignment will be organized into three sections: data collection, data cleaning for clarity, and a basic analysis to uncover patterns and insights that can help with the storytelling of the story behind the data.


## 2. Getting Data


##### To begin analyzing the dataset, I first imported it into Google Sheets, which is very helpful for clearing the format. I followed these steps to import the data:
1.	Find Google Sheets and go to File > Import.
![](ss1_file_to_import.png)
2.	Select Upload and find the CSV file extracted from Open Ottawa.
![](ss2_import_file.png)<br>
3.	Choose Replace spreadsheet to upload it as a new sheet, ensuring the data begins in cell A1, otherwise the format will be interrupted.
![](ss3_replace_spread_sheet.png)<br>
##### After importing, the dataset would be like this:
![](ss4_dataset_ap.png)<br>
The public link to this Google Sheets spreadsheet is here: 
https://docs.google.com/spreadsheets/d/1y2qkFr-wPx4Yjkibjxr8ryp7oQOLCHhHAUmfwWnDwZ8/edit?usp=sharing

As we can see, the dataset contains 28539 rows and 11 columns. From a first glance, it appears relatively clean, with most cells populated and formatted consistently. However, I noticed a few potential inconsistencies, especially in column F, H and I. Some of the “\N” are not aligning with others.

##### Specific Observations
1.	Column B: [Status] – This column contains categorical variables, representing status like resolved, active and cancelled.
o	Observation: The column is complete, clear and concise, nothing is missing.
2.	Column C: [Types] – This column contains different types of the requests, like Garbage and Recycling, Health and Safety.
o	Observation: There’s nothing wrong with the format of this column, everything’s in order.
3.	Column F: [Closed Date] – This column includes numerical variables, indicating the closed date of the specific request. 
o	Observation: A few dates are represented as “\N” as missing data, raising questions about what’s happening on those days and why the data is missing here.

##### Questions on the data
Looking at the data, one question that comes to my mind is: In the same type request, are there any correlations between one specific request’s description and its status for being resolved or cancelled? For example, for requests of Roads and Transportation, requests with a description of “road maintenance” are mostly tagged with “resolved”, yet most “active” tags have a description of “Traffic Management”. This could reveal how different factors impact city services.


## 3. Understanding Data

### 3.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As Cairo (2016) argues, a data visualization should be truthful...

### 3.2. Cleaning Data

Insert text here.

### 3.3. Exploratory Data Analysis (EDA)

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 4. Potential Story

Insert text here.

## 5. Conclusion

Insert text here.

## 6. References

Include a list of your references here. Please follow [APA guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
