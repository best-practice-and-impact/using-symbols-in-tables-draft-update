# Using symbols and shorthand in tables (draft version of update)
## Draft status 
This guidance is an update to the ['Using symbols and shorthand in tables'](https://gss.civilservice.gov.uk/policy-store/symbols-in-tables-definitions-and-help/) guidance on the [Government Statistical Service (GSS) website](https://gss.civilservice.gov.uk/). It is still under review. We are publishing a draft version to give civil servants early information on what they need to implement and to gather feedback. We continue to carry out research and testing. Once this is complete, the guidance will be updated on the GSS website.

If you have any questions or feedback, please email [gsshelp@statistics.gov.uk](mailto:gsshelp@statistics.gov.uk).
## Introduction
This guidance aims to provide a consistent shorthand to be used in tables, spreadsheets and other related documentation (such as methodology reports) published by the public sector. 

When we refer to shorthand we mean the use of a letter or letters as shorthand for a word or words. The use of symbols such as . : * or † is no longer recommended in spreadsheets because they can be difficult to see and screen reader software often won’t recognise them. This means they are likely to go against the [accessibility legislation](https://www.legislation.gov.uk/uksi/2018/852/contents/made). 

Whenever possible information should be given at the point of need, for example write out the word 'revised' rather than using 'r'. However, we know this is not always feasible in tables and spreadsheet. 

Using consistent shorthand across all public sector tables and spreadsheets will provide many [benefits to users](#Benefits-of-using-consistent-shorthand). 

## Layout of shorthand
Whenever a shorthand marker is presented in a table it should be in square brackets, for example: [r]. If you need to use more than one type of shorthand in the same cell, each should have its own square brackets, for example: [r][e]. This aids machine readability and makes it easier to spot shorthand.

Whenever a table contains shorthand, you should mention this and explain what the shorthand means, above the table. This will ensure users get this information before they come to the table itself. In spreadsheets this should be in a cell in column A as users of assistive technology will often navigate down from cell A1. 

For example you could present a sentence like this: 'Some shorthand is used in this table, [e] = estimated, [f] = forecast'. 

## Where to put shorthand
Ideally, shorthand should be presented in titles, column headings or row labels. They may also be placed within empty cells or to replace a data point in a cell. If they need to refer to a specific data point it is best to place them in a notes column added onto the right-hand side of a table. 

In terms of spreadsheets they should not be placed in cells with data as it can disrupt usability and machine readability. For example, if you want to sum a column but one of the data points has a shorthand marker next to it, this data point will get ignored. 

For more information on placement of shorthand in spreadsheets please see our '[Releasing statistics in spreadsheets](https://github.com/best-practice-and-impact/spreadsheet-accessibility/blob/main/interim-draft.md#Symbols-footnotes-and-codes)' guidance.

## The harmonised shorthand and when to use it

### b = break in time series
Use this shorthand when there is a break in a data series meaning that data before the break cannot be directly compared with data after the break. 

There are many reasons this can occur, including changes to: survey scope, sampling methods, questions, mode of data collection and weighting.

### c = confidential
This shorthand should be used when a data point would disclose confidential information (for example being able to identify details about a single respondent). These data points must be replaced with this shorthand to maintain confidentiality clauses.

In previous guidance there was a separate category for suppression. Discussion with the Statistical Disclosure Control Unit at the Office for National Statistics (ONS) confirmed that reasons for suppression would either be for confidentiality purposes or low reliability, and these are now identified separately in this list.

### e = estimated
This shorthand is to be used to indicate when a data point is estimated. Tables which are entirely estimates do not require a marker for each data point, provided titles or accompanying information make it clear that all figures are estimates.

### er = earliest revision
This shorthand should be used to signify a period for which the earliest revision was made in a particular time series. No other periods should be marked with a revision. 

An example from Public Sector Employment is the reclassification of public bodies. When colleges were reclassified from the private to the public sector, this increased the series by about 230,000 from 1993 onwards. Shorthand was used to indicate that the 1993 estimate was the point where revisions began. 

This shorthand is only to be used if there is an accompanying revision table for reference so that revisions over the period can be identified. This is not to be confused with 'revision'.

### f = forecast
This shorthand should be used to indicate when a data point is a calculated future value instead of an observed value. 

### low = a low figure but not a real zero 
This shorthand should replace data points that appear as zero in a rounded table, but are not actually zero. 

For example, international migration statistics published by the Office for National Statistics (ONS) report to the nearest thousand, so data points of 499 or less should be replaced with the word '[low]'. 

Note that '0' should only be used when a data point is a true zero.

### p = provisional
This shorthand should be used to indicate when data points are yet to be finalised, or are expected to be revised. 

### r = revised
This shorthand should be used to indicate when the data point presented has been revised since it was first published. Not to be confused with 'earliest revision'. 

### u = low reliability
This shorthand should be used to indicate when data points are of low quality. 

If communicating information about quality you should include (or link to) information explaning how quality information has been calculated and how data points have been classified. 

In previous guidance there was a separate category for suppression. Discussion with the Statistical Disclosure Control Unit at the Office for National Statistics (ONS) confirmed that reasons for suppression would either be for confidentiality purposes or low reliability, and these are now identified separately in this list.

### w = none recorded in survey
No people are estimated to be in this category, either because there were not any recorded by the survey or because none exist in the population.

### x = not available 
This shorthand should be used when data is unavailable for reasons other than those described in this list, for example, data not collected in a region. 

### z = not applicable
This shorthand should be used when a data point is not applicable. For example in tables of employment where people under 16 cannot legally be employed.

### Being more specific 
If you wish to be more specific in your shorthand it is OK to use numbers to specify the reasons. 
For example, if some data is of low reliability because it is calculated from a small number of data points and other data is of low reliability because the population base to choose from was very small you could use [u1] for the former reason and [u2] for the latter.   

### Shorthand for a reason not listed here 
If you cannot find shorthand listed here for something you need to signify in your tables, you can choose your own letter to use. But please check it is not one already in use on this list. Also, please let the team know as it may be something we need to add onto this list. Email: [GSSHelp@statistics.gov.uk](mailto:gsshelp@statistics.gov.uk).  

### Statistically significant
A statistically significant result is one that we are confident is not simply the result of random chance. 
 
If talking about statistical sigificance it is best practice to give information on how this is calculated and what it means for the data.

Note that the credibility of [assessing statistics using significance levels is currently under debate](https://www.nature.com/articles/d41586-019-00874-8).

#### ns = not significant
This shorthand can be used to indicate data points that are not statistically significant. 

When talking about different levels of significance, it has been common to use an asterisk symbol. However, as mentioned, symbols like an asterisk may be difficult to see for people with low vision and may be ignored by screen readers. We now advise to use the letter s in the following way:  

#### s = significant at 0.05 or 5% level

#### ss  = significant at 0.01 or 1% level

#### sss = significant at 0.001 or 0.1% level

When explaining what these levels mean you may want to say something along these lines: 

When we report on statistical significance, we are giving the likelihood of seeing this result if chance alone was operating. The phrase 'statistically significant at the 0.05 (or 5%) level' indicates that, if chance alone was operating, a result like this would occur less than 5% of the time.

### No to NA
We do not advise using 'NA' to describe cells with no data. This shorthand is ambiguous, some may read it as Not Applicable, others may read it as Not Available.

## Benefits of using consistent shorthand
### Increased understanding 
If shorthand is used consistently the meaning will become familiar to users.
### Ease of use and comparability 
For users who require multiple datasets, having multiple types of shorthand with multiple meanings can be time consuming and irritating. It can also increase the possibility of mistakes. Using consistent shorthand will make it easier to compare multiple datasets.
### Helping towards compliance 
If shorthand is used consistently it aids meeting the requirements of the three pillars of the Code of Practice for Statistics: Trustworthiness, Quality and Value. It also helps towards compliance with the Statistics and Registration Service Act 2007 Provision 9 - Definitions etc. for official statistics. This provision requires the development and maintenance of definitions, methodologies, classifications and standards for official statistics and promoting their use in relation to official statistics.
### Knowledge management 
Using consistent shorthand reduces vulnerability to staff turnover and improves communication with internal and external users.
### Efficient dissemination 
Consistent shorthand will help users understand our data more easily. This will increase efficiency and reduce the burden on staff responsible for answering questions.
### Improve integration 
Use of consistent shorthand will help with the integration of multiple data sources.
### Better information management 
Datasets are now accessible in many different ways, including direct digital access via Application Programming Interfaces (APIs). This enables users to bring together datasets from different sources quickly and easily. As the push for open data increases, and more departments service this demand, it will become increasingly important to standardise statistical content. Using consistent shorthand in data published across government is a step towards facilitating these new uses of statistics. 
