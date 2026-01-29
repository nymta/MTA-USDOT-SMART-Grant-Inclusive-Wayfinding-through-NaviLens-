# MTA-USDOT-SMART-Grant-Inclusive-Wayfinding-through-NaviLens-
This repository contains all data and metadata from the MTA's FY22 SMART Grant Stage 1 project: Inclusive Wayfinding through NaviLens. Data contains usage of and feedback on the NaviLens and NaviLens GO wayfinding, information access, and language translation apps.

README for MTA NaviLens Usage dataset. SCROLL TO LINE 176 FOR README for MTA NaviLens Feedback Survey dataset. 
Strengthening Mobility and Revolutionizing Transportation (SMART) Program, U.S. Department of Transportation (USDOT)
2026-01-16

----------------------------------------------------------------
LINKS TO DATASET
----------------------------------------------------------------

A. Dataset archive link: https://data.ny.gov/Transportation/MTA-NaviLens-Usage/kag2-r3f3/about_data

B. Final Dataset DOI: https://doi.org/10.21949/ph7t-4944

C. Data Management Plan DOI: https://doi.org/10.48321/D1R67H


----------------------------------------------------------------
SUMMARY OF DATASET
----------------------------------------------------------------
Navilens usage data contains records of scan events (each row represents a time a NaviLens code was scanned). Scan records include the code identifier, the type of asset scanned (e.g., bus stop, bus vehicle, subway station, train car, or vehicle feature), the app used (NaviLens vs. NaviLens GO), the device language setting at time of scan, and timestamps. For certain asset types, scan events are also enriched with location fields such as bus stop identifiers and names or subway station identifiers and names. This data supports evaluation of the NaviLens deployment and related project reporting, including work funded through the USDOT SMART Grant.



----------------------------------------------------------------
TABLE OF CONTENTS
----------------------------------------------------------------

A. General Information
B. Sharing/Access & Policies Information
C. Data and Related File Overview
D. Methodological Information
E. Data-Specific Information for: MTA NaviLens Usage
F. Update Log


----------------------------------------------------------------
A. GENERAL INFORMATION
----------------------------------------------------------------

0. Title of Dataset: MTA NaviLens Usage


1. Description of Dataset:  

This dataset contains NaviLens usage data, meaning records of scan events (each row represents a time a NaviLens code was scanned). Scan records include the code identifier, the type of asset scanned (e.g., bus stop, bus vehicle, subway station, train car, or vehicle feature), the app used (NaviLens vs. NaviLens GO), the device language setting at time of scan, and timestamps. For certain asset types, scan events are also enriched with location fields such as bus stop identifiers and names or subway station identifiers and names. This data supports evaluation of the NaviLens deployment and related project reporting, including work funded through the USDOT SMART Grant.

   

2. Dataset archive link: https://data.ny.gov/Transportation/MTA-NaviLens-Feedback-Survey/q2wi-uth2/about_data


3. Authorship Information: 
   Principal Data Creator or Data Manager Contact Information
      Name: Miriam Philipson
      ORCID: 0009-0007-9551-538X
      Institution: Metropolitan Transportation Authority (NY)
      Address: 2 Broadway, New York, NY 10004
      Email: miriam.philipson@mtahq.org

   Associate Data Creator or Data Manager Contact Information
      Name: Christine Singh
      ORCID: 0009-0004-8728-3505
      Institution: Metropolitan Transportation Authority (NY)
      Address: 2 Broadway, New York, NY 10004
      Email: christine.singh@mtahq.org 
  
   Organizational Contact Information
      Name: Metropolitan Transportation Authority Accessibility
      Institution: Metropolitan Transportation Authority (NY)
      Address: 2 Broadway, New York, NY 10004
      Email: opendata@mtahq.org
	   
	   
4. Date of data collection and update interval: July 2024-August 2025
   

5. Geographic location of data collection: New York, New York, United States of America


6. Information about funding sources that supported the collection of the data:
   This dataset package was funded through the USDOT Strengthening Mobility and Revolutionizing Transportation (SMART) Program. The grant number for this project is: SMARTFY22N1P1G45



----------------------------------------------------------------
B. SHARING/ACCESS & POLICIES INFORMATION 
----------------------------------------------------------------

0. Recommended citation for the data: 
   Philipson, Mira and Singh, C. (2026). MTA NaviLens Usage Data [datasets]. doi.org/10.21949/ph7t-4944
    

1. Licenses/restrictions placed on the data:
   These data are in the Public Domain.


2. Was data derived from another source?:
   No.
   
   
3. This dataset and its documentation was created and shared to meet the requirements enumerated in the U.S. Department of Transportation's "Plan to Increase Public Access to the Results of Federally-Funded Scientific Research" Version 1.1 << https://www.transportation.gov/sites/dot.gov/files/docs/Official%20DOT%20Public%20Access%20Plan%20ver%201.1.pdf >> and guidelines suggested by the DOT Public Access website << https://ntl.bts.gov/publicaccess/ >>, in effect and current as of April 10, 2019.



----------------------------------------------------------------
C. DATA & RELATED FILE OVERVIEW
----------------------------------------------------------------

1. File List for the MTA_NaviLens_Usage.zip collection      
        
   A. Filename: MTA_NaviLensUsage_Overview.pdf
          
        Short description: A PDF file of a general description and summary of NaviLens usage dataset.       
         

   B. Filename: MTA_NaviLensUsage_DataDictionary.pdf
           
        Short description: A PDF file of a list of all data labels found in usage data with description and data type. 
      

   C. Filename: MTA_NaviLensUsage_20260115.csv
           
        Short description: A CSV file of all recorded data of all NaviLens codes scanned from July 2024 to August 2025. 

        


----------------------------------------------------------------
D. METHODOLOGICAL INFORMATION
----------------------------------------------------------------

1. Description of methods used for collection/generation of data:

NaviLens scan data are collected automatically by NaviLens every time a NaviLens code is scanned. The data is anonymized per MTA Cybersecurity requirements and delivered to the MTA by NaviLens in CSV format. The data was then changed to the local time zone for accuracy, and details for the locations of each code were added as well.

Operationally, NaviLens codes were deployed at select locations (including listed Manhattan and Bronx subway stations and on routes such as Bx12/Bx12-SBS, M23 SBS, and M66), and the scan data is specific to codes located in these environments as part of the MTA’s USDOT SMART Grant Stage 1 project. 
     
   


----------------------------------------------------------------
E. DATA-SPECIFIC INFORMATION  
----------------------------------------------------------------

1. MTA_NaviLensUsage_20260115.csv

A. Number of variables (columns): 14


B. Number of cases/rows: 126K
   

C. Each row represents: 1 code identifier, code name, type of asset, app used, device language, and timestamp
  

D. Data Dictionary/Variable List: MTA_NaviLensUsage_DataDictionary.pdf


E. Missing data codes: N/A




----------------------------------------------------------------
F. UPDATE LOG
----------------------------------------------------------------

This README_MTA_NaviLensUsage file was originally created on 2026-01-16 by Christine Singh, 0009-0004-8728-3505, Accessibility Projects Specialist, christine.singh@mtahq.org

Update Log:
2026-01-16: Original file created

______________________________________________________________________________________________________________________________________________________________________________________ 


README for MTA NaviLens Feedback Survey dataset. 
Strengthening Mobility and Revolutionizing Transportation (SMART) Program, U.S. Department of Transportation (USDOT)
2026-01-16

----------------------------------------------------------------
LINKS TO DATASET
----------------------------------------------------------------

A. Dataset archive link: https://data.ny.gov/Transportation/MTA-NaviLens-Feedback-Survey/q2wi-uth2/about_data
B. Final Dataset DOI: https://doi.org/10.21949/ph7t-4944
C. Data Management Plan DOI: https://doi.org/10.48321/D1R67H


----------------------------------------------------------------
SUMMARY OF DATASET
----------------------------------------------------------------
This dataset contains responses from the MTA NaviLens feedback survey, which collects customer feedback on NaviLens and NaviLens GO, two accessibility and wayfinding smartphone apps used with brightly colored NaviLens codes installed across select MTA subway stations, subway cars, bus stops, and buses. NaviLens is designed primarily for riders who are blind or have low vision by translating signage and wayfinding information into audio, while NaviLens GO provides similar information in a visual format and includes features such as upcoming arrivals, systemwide service status, and elevator/escalator status.



----------------------------------------------------------------
TABLE OF CONTENTS
----------------------------------------------------------------

A. General Information
B. Sharing/Access & Policies Information
C. Data and Related File Overview
D. Methodological Information
E. Data-Specific Information for: MTA NaviLens Feedback Survey
F. Update Log


----------------------------------------------------------------
A. GENERAL INFORMATION
----------------------------------------------------------------

0. Title of Dataset: MTA NaviLens Feedback Survey


1. Description of Dataset: 

Survey responses include overall satisfaction, agreement ratings about ease of use and information quality, recommendations, interest in expanding code coverage, comparisons to other wayfinding/travel apps, and open-ended comments. The survey also includes optional demographic questions (e.g., age range, typical transit use frequency, Access-A-Ride customer status, and disability identification) to help contextualize feedback. This survey supports evaluation of the NaviLens deployment and related project reporting, including work funded through the USDOT SMART Grant.
   

2. Dataset archive link: https://data.ny.gov/Transportation/MTA-NaviLens-Feedback-Survey/q2wi-uth2/about_data


3. Authorship Information: 
   Principal Data Creator or Data Manager Contact Information
      Name: Miriam Philipson
      ORCID: 0009-0007-9551-538X
      Institution: Metropolitan Transportation Authority (NY)
      Address: 2 Broadway, New York, NY 10004
      Email: miriam.philipson@mtahq.org

   Associate Data Creator or Data Manager Contact Information
      Name: Patrick Sciallis
      ORCID: 0009-0001-8183-612X
      Institution: Metropolitan Transportation Authority (NY)
      Address: 2 Broadway, New York, NY 10004
      Email: patrick.sciallis@mtahq.org 

   Associate Data Creator or Data Manager Contact Information
      Name: Christine Singh
      ORCID: 0009-0004-8728-3505
      Institution: Metropolitan Transportation Authority (NY)
      Address: 2 Broadway, New York, NY 10004
      Email: christine.singh@mtahq.org 
  
   Organizational Contact Information
      Name: Metropolitan Transportation Authority Accessibility
      Institution: Metropolitan Transportation Authority (NY)
      Address: 2 Broadway, New York, NY 10004
      Email: opendata@mtahq.org
	   
	   
4. Date of data collection and update interval: May 2025-August 2025
   

5. Geographic location of data collection: New York, New York, United States of America


6. Information about funding sources that supported the collection of the data:
   This dataset package was funded through the USDOT Strengthening Mobility and Revolutionizing Transportation (SMART) Program. The grant number for this project is: SMARTFY22N1P1G45



----------------------------------------------------------------
B. SHARING/ACCESS & POLICIES INFORMATION 
----------------------------------------------------------------

0. Recommended citation for the data: 
   Sciallis, Patrick, Philipson, M., and Singh, C. (2026).  MTA NaviLens Feedback Survey [datasets]. https://doi.org/10.21949/ph7t-4944


1. Licenses/restrictions placed on the data:
   These data are in the Public Domain.


2. Was data derived from another source?:
   Yes, feedback survey was hosted on Qualtrics.com
   
   
3. This dataset and its documentation was created and shared to meet the requirements enumerated in the U.S. Department of Transportation's "Plan to Increase Public Access to the Results of Federally-Funded Scientific Research" Version 1.1 << https://www.transportation.gov/sites/dot.gov/files/docs/Official%20DOT%20Public%20Access%20Plan%20ver%201.1.pdf >> and guidelines suggested by the DOT Public Access website << https://ntl.bts.gov/publicaccess/ >>, in effect and current as of April 10, 2019.



----------------------------------------------------------------
C. DATA & RELATED FILE OVERVIEW
----------------------------------------------------------------

1. File List for the README.zip collection      
        
   A. Filename: MTA_NaviLensFeedbackSurvey_Overview.pdf
          
        Short description: A PDF file of a general description and summary of NaviLens feedback survey dataset.        
         

   B. Filename: MTA_NaviLensFeedbackSurvey_DataDictionary.pdf
           
        Short description: A PDF file of a list of all data labels found in survey data with description and data type. 
      

   C. Filename: MTA_NaviLens_Feedback_Survey_20260115.csv
           
        Short description: A CSV file of all recorded data of all responses from May to August 2025 to each question in the survey for both NaviLens and NaviLens GO apps. 


   C. Filename: MTA_NaviLensFeedbackSurvey_Flow.pdf
           
        Short description: A PDF file of a blank copy of the feedback survey questions for both NaviLens and NaviLens GO apps.
        


----------------------------------------------------------------
D. METHODOLOGICAL INFORMATION
----------------------------------------------------------------

1. Description of methods used for collection/generation of data: 

Survey data are collected through an online questionnaire, hosted via Qualtrics. It includes both completed and partially completed responses. MTA Responses follow survey logic (skip patterns) based on which app(s) the respondent selected and where they reported using the app (e.g., subway station/train vs. bus stop/bus), so not all columns apply to every response.

Operationally, NaviLens codes were deployed at select locations (including listed Manhattan and Bronx subway stations and on routes such as Bx12/Bx12-SBS, M23 SBS, and M66), and the survey is intended for customers who used NaviLens in these environments.
     

   


----------------------------------------------------------------
E. DATA-SPECIFIC INFORMATION  
----------------------------------------------------------------

1. MTA_NaviLens_Feedback_Survey_20260115.csv

A. Number of variables (columns): 55


B. Number of cases/rows: 159
   

C. Each row represents: overall satisfaction, agreement ratings, open-ended comments, optional demographic questions, and recorded timestamp
  

D. Data Dictionary/Variable List: MTA_NaviLensFeedbackSurvey_DataDictionary.pdf





----------------------------------------------------------------
F. UPDATE LOG
----------------------------------------------------------------

This README_MTA_NaviLensFeedbackSurvey file was originally created on 2026-01-16 by Christine Singh, 0009-0004-8728-3505, Accessibility Projects Specialist, christine.singh@mtahq.org

Update Log:
2026-01-16: Original file created
