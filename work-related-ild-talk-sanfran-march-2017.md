% Work-related Interstitial Lung Disease: Beyond pneumoconiosis 
% Dr Carl Reynolds 

# Disclosures

## I have nothing to disclose 

# Supporting materials

##

> https://github.com/drcjar/work-related-ild-talk-sanfran-march-2017


# Today you will learn (if you didn't know it already)

##

1. The difference between colophon and colophony  
2. The difference between python and python 
3. What the GP Prescribing Data is and why it's fun 

# Christmas Colophon Quiz

## which of the following is not a colophon?

##

- A. a city in ancient Greece, located in modern Turkey
- B. a small genus of beetles in the stag beetle family Lucanidae
- C. a brief statement containing information about the publication of a book such as the place of publication, the publisher, and the date of publication
- D. a rumbling, growling or gurgling noise produced by movement of the contents of the gastro-intestinal tract 

## Can you identify the following?

## Exhibit 1 

## {data-background="images/colophon1.jpg"}

## Exhibit 2 
 
## {data-background="images/colophon2.jpg"}

## Exhibit 3 

## {data-background="images/colophon3.jpg"}

## Exhibit 4 

## {data-background="images/colophon4.jpg"}

# Christmas Python Quiz

## Python (the programming language) is named after:

## {data-background="images/python1.jpg"}

## {data-background="images/python2.jpg"}

# Christmas Prescribing Quiz

## Not really or at least not yet

# What GP Prescribing Data is

## An overview

##
1. A monthly timeseries since August 2010
2. "Presentation-level" prescribing data for all GP practices in England
3. Over 70,000 different drugs, about 8000 practices, 10 columns, over 4 million rows, per month for 72 months to date (well over 80gb of data)
4. [Organisation Data Service](https://digital.nhs.uk/organisation-data-service) release a wealth of supporting data (all documented in a single 158 page pdf)
5. All released under the OGL (Open Government Licence) by NHS Digital (formerly HSCIC). Sometimes some data (e.g dispensing practices) also released by NHS Business Services Authority...

## Presentation-level data

##
- Strategic health authority (SHA) code (3 characters)
- Primary care trust (PCT) code (3 characters)
- Practice code (6 characters)
- British National Formulary (BNF) code (15 characters) 
- BNF name (truncated to 40 characters) 
- Total Items
- Total Net Ingredient Cost (£) 
- Total Actual cost (£) 
- Quantity
- Processing date (YYYYMM)

## Challenges
- variable amounts of white space in the data
- not all gp practices are gp practices...
- the BNF code is no the BNF code
- denominators

##

- 0 = Other
- 1 = WIC Practice
- 2 = OOH Practice
- 3 = WIC + OOH Practice
- 4 = GP Practice
- 8 = Public Health Service
- 9 = Community Health Service
- 10 = Hospital Service
- 11 = Optometry Service
- 12 = Urgent & Emergency Care

##

- 13 = Hospice
- 14 = Care Home / Nursing Home
- 15 = Border Force
- 16 = Young Offender Institution
- 17 = Secure Training Centre
- 18 = Secure Children's Home
- 19 = Immigration Removal Centre
- 20 = Court
- 21 = Police Custody
- 22 = Sexual Assault Referral Centre (SARC)
- 24 = Other

##

Prescribing data uses modified version of BNF which was current in 2014

## 
![bnf_code_understander](images/bnf_code_understander.png)


## denominators

- list size?
- STAR-PU
- proportions

# Why GP Prescribing Data is fun

## Example project(s) 

##

## prescribing analytics
## open prescribing
## dispensing vs non-dispensing practices
## datasift mans work
## puffer prescriber primer

# Christmas Prescribing Quiz

##
Which of the following is statements is true?

- A. NHS Digital data releases follow standard consistent file naming formats
- B. NHS Digital metadata releases are easily accessible on the web and not hidden away inside pdfs
- C. All of the supporting data needed to work with GP Prescribing data is readily available in one place
- D. GP Prescribing Data has some shortcomings but can be fun to work with


# Questions?
##

# Carl's colophon? 

## How this presentation was made

##
- written in markdown using vim
- converted to revealjs with pandoc
- jupyter and pandas used for analysis
- static content served using github
- repository lives at: 

> https://github.com/drcjar/prescribing-seminar-dec2016/


