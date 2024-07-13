# Automation-Assignment
ChicMic Automation Assignment


**Project Setup and Implementation Status:**
1. **Environment Requirements:**
   - The project requires JDK 17 to run.

2. **Framework Implementation:**
   - Successfully implemented the framework with Extent Reports integration.
   - Positive scenarios have been fully covered and are functioning as expected.

3. **Test Coverage:**
   - Negative scenarios have been implemented for the login screen.
   - Unable to proceed with further test development due to login issues on the platform.
   - Creation of different test suites is currently blocked by the same login error.
   - This limitation has been communicated to the team.

4. **Pending Tasks:**
   - Attempted to schedule interviews, but encountered a server-side error ("Something went wrong").
   - As a result, several planned tasks could not be completed.
   - This issue has been reported to both HR and the development team.

In summary, while the basic framework and positive scenarios are in place, further progress is hindered by login and server-side issues. These problems have been escalated to the appropriate teams for resolution.

The following mentioned tasks are done:
1. Add Candidate: ( Done )
- Prompt the user to input the candidate's details, ensuring uniqueness of the candidate 
name. 
- Collect basic details including all required fields. 
- Handle experience details dynamically, including the total experience with a date picker. 
- Validate input data for correctness and completeness. 
- Add the candidate along with their details to the interview module. 
- Provide error handling for invalid inputs or failures during the addition process. 

2. Candidate List: ( Done )
- Calculate total records from a table listing, considering pagination in a dynamic approach. 

3. Screening Request: ( Done )
- Accept or reject screening requests, prioritising the Accept action only. 
- Move approved requests to the candidate list. 

4. Candidate List (Continued): 
- Choose scheduled interview action. ( Done )
- Fill all required values dynamically. ( Done )
Field choose as below : 
- Select Interview platform as 'face to face'. ( Done )
- Choose the team and interviewer as per provided credential. ( Done ) 
 -> Not able to select the QA interviewer because not getting the all interviewer in list, so I scheduled the same with CEO

- Select the date for today and ensure the time is +5 or 10 minutes from the local time so 
that accept or feedback popup appears for interviewer  -> Done



The following mentioned tasks are not done because when I try to schedule the interview it server side error i.e. “Something went wrong”, I informed the same to the HR and Team :-
- Check Live status based on provided details: First round/pending/rejected. 
5. Interviewer Process: 
- Login with interviewer portal credentials. 
- Select the interview and interview request. 



Thanks & Regards,
Simranjit Singh
