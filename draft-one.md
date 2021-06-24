# Using symbols and shorthand in tables (draft version of update)
## Draft status 
This guidance is an update to the ['Using symbols and shorthand in tables'](https://gss.civilservice.gov.uk/policy-store/symbols-in-tables-definitions-and-help/) guidance on the [Government Statistical Service (GSS) website](https://gss.civilservice.gov.uk/). It is still under review. We are publishing a draft version to give civil servants early information on what they need to implement and to gather feedback. We continue to carry out research and testing. Once this is complete, the guidance will be updated on the GSS website.

If you have any questions or feedback, please email [gsshelp@statistics.gov.uk](mailto:gsshelp@statistics.gov.uk).
## Introduction
This guidance aims to provide a consistent shorthand to be used in government spreadsheets and other related documentation (such as methodology reports). 

When we refer to shorthand we mean the use of a letter or letters as shorthand for a word or words. The use of symbols such as . : * or † is no longer recommended in spreadsheets because they can be difficult to see and screen reader software often won’t recognise them. This means they are likely to fail the [accessibility legislation](https://www.legislation.gov.uk/uksi/2018/852/contents/made). 

Whenever possible information should be given at the point of need, for example write out the word 'revised' rather than using 'r'. However, we know this is not always feasible in tables of statistics. 

Using consistent shorthand across government statistical outputs will provide many [benefits to users](#Benefits-of-harmonising-shorthand). 

## Layout of shorthand
Shorthand markers should be presented in column headings, row labels or by adding on a notes column to a table. They should not be placed in cells with data. For more information please refer to our '[Releasing statistics in spreadsheets](https://github.com/best-practice-and-impact/spreadsheet-accessibility/blob/main/interim-draft.md#Symbols-footnotes-and-codes)' guidance. 

Whenever a shorthand marker is presented in a table it should be in square brackets, for example: [r]. If you need to use more than one shorthand marker in the same cell, each should have its own square brackets, for example: [r][e]. This aids machine readability and makes it easier to spot shorthand.

Whenever a table contains shorthand markers, you should mention this in a cell in column A above the table so users get this information before they come to the table itself. For example 'Some shorthand is used in this table, [e] = estimated, [f] = forecast'. 

## The harmonised shorthand and when to use it

### b = break in time series
Use this shorthand when there is a break in a data series meaning that data before the break cannot be directly compared with data after the break. 

There are many reasons this can occur, including changes to: survey scope, sampling methods, questions, mode of data collection and weighting.

### c = confidential
This shorthand should be used when a data point would disclose confidential information (for example being able to identify details about a single respondent). These data points must be replaced with this shorthand to maintain confidentiality clauses.

In previous guidance there was a separate category for suppression. Discussion with the Statistical Disclosure Control Unit at the Office for National Statistics (ONS) confirmed that reasons for suppression would either be for confidentiality purposes or low reliability, and these are now separately identified in this list.

### er = earliest revision
This shorthand should be used to signify a period for which the earliest revision was made in a particular time series. No other periods should be marked with a revision. 

An example from Public Sector Employment is the reclassification of public bodies. When colleges were reclassified from the private to the public sector, this increased the series by about 230,000 from 1993 onwards. A marker was placed next to the 1993 estimate to indicate that this was the point where revisions began. 

This shorthand is only to be used if there is an accompanying revision table for reference so that revisions over the period can be identified. This is not to be confused with 'revision' below.

### e = estimated
This shorthand is to be used to signify when a data point is estimated in a way that is different to the rest of data presented. 

Tables which are entirely estimates do not require a marker for each data point, provided titles or accompanying information make it clear that all figures are estimates.

### f = forecast
This shorthand should be used when a data point is a calculated future value instead of an observed value. 

### low = less than half the final digit shown and different from a real zero 
This shorthand should replace data points that appear as zero in a rounded table, but are not actually zero. 

For example, international migration statistics published by the Office for National Statistics (ONS) report to the nearest thousand, so data points of 499 or less should be replaced with the word '[low]'. 

Note that '0' should only be used when a data point is a true zero.

### u = low reliability
This shorthand should be used to indicate when data points are of low quality. 

If communicating information about quality you should include (or link to) information explaning how quality information has been calculated and how data points have been classified. 

### z = not applicable
This shorthand should be used when a data point is not applicable. For example in tables of employment where people under 16 cannot legally be employed.

### x = not available 
This shorthand should be used when data is unavailable for reasons other than those described in this list, for example, data not collected in a region. 

### p = provisional
This shorthand should be used to signify when data points are yet to be finalised, or are expected to be revised. 

### r = revised
This shorthand should be used when the data point presented has been revised since it was first published. Not to be confused with 'earliest revision'. 

### Statistically significant
A statistically significant result is one that we are confident is not simply the result of random chance. The fact that a result is statistically significant does not mean that it is necessarily of practical importance. For example, if sample sizes are large, small differences can be statistically significant. Only by considering context can we determine whether a difference is important enough to require action.

#### ns = not significant
This shorthand can be used to signify data points that are not statistically significant. For the majority of UK statistics it is more useful to know the level of significance, which is why we also have shorthand for levels of statistical significance. 

#### s = significant at 0.05 level
When we report on statistical significance, we provide an assessment of how likely it is that we would see results as unusual as these if chance alone was operating. The phrase 'statistically significant at the 0.05 (or 5%) level' indicates that, if chance alone was operating, a result like this would occur less than 5 times in 100, or less than 5% of the time.

#### ss  = significant at 0.01 level
When we report on statistical significance, we provide an assessment of how likely it is that we would see results as unusual as these if chance alone was operating. The phrase 'statistically significant at the 0.01 (or 1%) level' indicates that, if chance alone was operating, a result like this would occur less than 1 times in 100, or less than 1% of the time.

#### sss = significant at 0.001 level
When we report on statistical significance, we provide an assessment of how likely it is that we would see results as unusual as these if chance alone was operating. The phrase 'statistically significant at the 0.001 (or 0.1%) level' indicates that, if chance alone was operating, a result like this would occur less than 0.1 times in 100, or less than 0.1% of the time.

## Where to put shorthand
Ideally shorthand markers should be used after titles, in column headings, row labels or within empty cells.  

There may be situations where you need to put them in cells with data. We advise against doing this as it can disrupt usability and machine readability. For example, if you want to sum a column but one of the data points has a shorthand marker next to it, this data point will get ignored.  

If a specifc data cell needs a piece of information attached to it, we advise you to add a notes column to your table on the right and put shorthand or note markers in here, specifying which cells the shorthand or note refers to. More information on this can be found in our [Releasing statistics in spreadsheets](https://github.com/best-practice-and-impact/spreadsheet-accessibility/blob/main/interim-draft.md) guidance. 


## Benefits of harmonising shorthand
### Increased understanding 
If shorthand is used consistently then no matter what data users’ access, the symbols and their meanings will be consistent and familiar.
### Ease of use and comparability 
For data users who require multiple datasets, having multiple types of shorthand with multiple meanings could not only be arduous and time consuming but also increase the possibility of mistakes. Harmonised shorthand will allow comparability between multiple datasets.
### Helping towards compliance 
If harmonised shorthand is used it aids meeting the requirements of the three pillars of the Code of Practice for Statistics: Trustworthiness, Quality and Value. It also helps towards compliance with the Statistics and Registration Service Act 2007 Provision 9 - Definitions etc. for official statistics, which requires the development and maintenance of definitions, methodologies, classifications and standards for official statistics and promoting their use in relation to official statistics.
### Knowledge management 
Use of harmonised shorthand reduces vulnerability to staff turnover by sharing knowledge within the organisation, encouraging dissemination of good practice and improving communication with internal and external users.
### Efficient dissemination 
Harmonised shorthand will facilitate self-help for users of data on the web, thereby increasing efficiency and reducing burden on staff responsible for answering questions.
### Comparability for cross survey analysis and integration 
Use of harmonised shorthand will increase access to data from different sources and make them comparable across time and source. Provision of consistent data markers will enable the comparison of statistical products and create an environment in which multiple data sources can be integrated.
### Improving the quality of data 
Harmonised shorthand can be used to reduce avoidable differences in understanding different outputs which can be caused by use of different shorthand.
### Better information management 
Datasets are now accessible in many different ways, including direct digital access via Application Programming Interfaces (APIs). This enables users to bring together datasets from different sources quickly and easily. As the push for open data increases, and more departments service this demand, it will become increasingly important to standardise statistical content. A single set of harmonised shorthand is a step towards facilitating these new uses of statistics. 
