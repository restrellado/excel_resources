Predicting Data Identified Non-Compliance
================
Ryan Estrellado
8/9/2018

This document has information used to support my CEDR 2018 presentation on predicting data identified non-compliance (DINC). It’s a big topic and I can’t cover everything I want to, so I hope this helps supplement the hour-long talk. This document will change over time, so you can visit the online version on my [GitHub page](https://github.com/restrellado/excel_resources/blob/master/one_page_handout.md) for a more recent version. If you have feedback or any questions, please contact me at <restrellado@sdcoe.net> or call me at 619-470-5233. - Ryan

### Support Materials

The California Department of Education’s [CASEMIS Technical Assistance Guide](https://www.cde.ca.gov/sp/se/ds/documents/dec2017casemistag.doc) defines every CASEMIS field, including the ones we use to make our DINC predictions. You can download the latest version of the CASEMIS TAG on the CDE website.

[Here is a link](https://www.dropbox.com/sh/0autz417lgoqbk0/AACuVFYObgf2bBYUe1tkyQjva?dl=0) to the slides, excel spreadsheets, and screenshots I used during my presentation.

[This is a link](https://github.com/restrellado/excel_resources/blob/master/excel_resources.md) to some Excel resources I gathered that teach you operations I used in my presentation. These are just a few I found- there is a lot of online reading available about Excel. If you find others, feel free to email me and I can add them to the document.

### Summary of DINC Criteria

You can estimate DINC records by using the following fields:

-   Overdue 60 day timelines: Initial evaluation date is more than 60 days after the parent consent date and there is no EVLDLAY code
-   Overdue annual reviews: The last IEP is more than one year earlier than the report date and there is no IEPDELAY code
-   Overdue triennial evaluations: The last evaluation date is more than three years earlier than the report date and there is no TRIDELAY code
-   Overdue third birthday evaluations: The initial evaluation date is more than three years after the birthdate and there is no TBDLAY code
-   Transition: transition fields 1 through 7 are not code 10 and transition field 8 is not code 20

### How to Make Better Predictions

Improving your predictions is a process. These practices will improve your craft over time:

-   Record your predictions and compare them to CDE's results
-   Keep your Excel skills sharp to make your process run quickly
-   Make predictions frequently and early
-   Try reproducing another of CDE's compliance scores

### Next Steps

Consider learning how to code in a language like [R](https://www.r-project.org/about.html) or [Python](https://www.python.org/) to make your procedures faster, more reproducible, shareable, and scalable.
