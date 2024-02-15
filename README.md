# RSS_summary_documents
This markdown automates the creation of climate summaries that are included in RSS documents. 
The historical trends and climate futures information is drafted and the RSS lead will need to add content at the end detailing park-specific climate sensitivities that were IDed during the RSS process. 

## Instructions
1. Use the RSS_Climate_Summary.Rmd
2. Change park-specific information: 
    a. SiteID and park name 
    b. Directories where the climate futures and historical climate information are stored. 
    c. Name region where park is located
    d. Set CFs used in the RSS
  
If the folders were copied as they are ouput from R scripts, the document will read in the dataframes and insert correct info from there. 

3. Go to https://statesummaries.ncics.org/ and look up the state where the park is located. Copy one of the key message sentences into the variable State_summary_statement; add the citation to State_summary_reference.

4. Knit the Rmd. If there are errors, troubleshoot and/or contact Amber Runyon. 
5. Copy RSS_Climate_Summary.docx to RSS folder and add "_PARKCODE" to the end of the name
6. The 4th paragraph will require some editing. It's easier to do this manually than to code it then have to review it anyway. The Rmd will print out the information that is used to fill in the sentence.
    a. Modify sentences describing the seasonal trends in changing precipitation
    b. Modify sentence describing changing drought characteristics. 
This should read as one paragraph after changes have been made. Delete all extra information.

7. Proofread the document. If it looks like there are any errors, fix them and contact Amber if they came from coding errors. 
