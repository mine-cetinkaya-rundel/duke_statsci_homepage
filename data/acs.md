---
layout: data_dictionary
title: acs.RData
---

### Get the data


Two options listed below:

1. Click <a href="acs.RData" download="acs.RData">
*here*
</a> to download the dataset.


2. Alternatively, use the following lines of code to load the data in R using the following:

<div class="highlight">
    <code>
    load(url(https://stat.duke.edu/~mc301/data/acs.RData))
    </code>
</div>

### Data description

Each year since 2005, the US Census Bureau surveys about 3.5 million households with The American Community Survey (ACS). Data collected from the ACS have been crucial in government and policy decisions, helping to determine the allocation of more than $400 billion in federal and state funds each year. For example, funds for the Adult Education and Family Literacy Act are distributed to states taking into consideration data from the ACS on number of adults 16 and over without a high school diploma. This act is the primary source of federal funding for adults with low basic skills seeking further education or English language services, and Department of Education uses ACS data to ensure the efficient distribute funds.
The ACS received a surge of media attention in spring 2012 when the House of Representatives voted to eliminate the survey. Daniel Webster, a first-term Republican congressman from Florida, sponsored the legislation citing the following reasons:

<small>
"This is a program that intrudes on peoples lives, just like the Environmental Protection Agency or the bank regulators."
<br>
"We're spending $70 per person to fill this out. That's just not cost effective."
<br>
"In the end this is not a scientific survey. Its a random survey."
<br>
</small>

This dataset, given that it comes from a "random survey", can be used to make inferences about the US population at large.

### Codebook

This data frame contains 152 observations (rows), each representing a Duke Sta 101 student, and 53 variables (columns):

1. `income` - Yearly income (wages and salaries)

2. `employment` - Employment status
    + `not in labor force`
    + `unemployed`
    + `employed`

3. `hrs_work` - Weekly hours worked

4. `race` - Race 
    + `White`
    + `Black`
    + `Asian`
    + `other`

5. `age` - Age in years

6. `gender` - Gender
    + `male`
    + `female`

7. `citizen` - Whether respondent is a US citizen or not
    + `yes`
    + `no`

8. `time_to_work` - Travel time to work, in minutes

9. `lang` - Language spoken at home
    + `English`
    + `other`

10. `married` - Whether respondent is married or not
    + `yes`
    + `no`

11. `edu` - Education level
    + `hs or lower`
    + `college`
    + `grad`

12. `disability` - Whether respondent is disabled or not
    + `yes`
    + `no`

13. `birth qrtr` - Quarter in which respondent is born 
    + `Jan thru Mar`
    + `Apr thru Jun`
    + `Jul thru Sep`
    + `Oct thru Dec`
