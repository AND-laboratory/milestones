# milestones
Sexual identity milestones in Gen Z young people - cross-sectional 2023 study. The survey provided is the only study materials used. The markdown scripts provided are for the primary analyses and are presented in order of the planned statistical analyses discussed in the article.

You may see mention of an additional interview follow-up in the survey, this is connected to a separate project with different research questions.

If you wish to re-use the analysis scripts to reproduce the results reported in the manuscript, you must use RStudio and Mplus software. All required r-packages are listed in each of the script files under the heading 'packages'. Open the relevant script file and set the working directory to where you have saved the downloaded data file. This is shown in the 'setup' section of code in each script file. You will then be able to run the script. The data file 'GZMCoreDataRaw' shows how the data was cleaned and prepared and should be paired with the '0. Milestone Data Prep' file. This data file uses a more unrefined dataset initially, though identifiable information has still been removed from this - including some TEXT columns where participants provided manual inputs to demographic questions, some of which were quite detailed and potentially identifiable in combination with other data. Text input columns already removed include: 

- neurodivergence and disability status; reasoning is unique combinations of disorders and conditions listed can be identifiable in combination with other data
- state/territory of residence, race, ethnicity, and religion; same reasoning as above (this can be released to any interested university-affiliated academic on request)
- school type; Australia has a lot of unique private schools and religious schools, especially by different state, so these can be easily identifiable in combination with other data
- specific family member who participants came out to; was not used in analysis and is identifiable based on specific response cases as additional context was often given

After this the data file will match the 'GZMCore' data file, which can be used on the remaining script files.

This work is marked with CC0 1.0 Universal.
