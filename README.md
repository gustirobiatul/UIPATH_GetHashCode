# UIPATH_GetHashCode
This is the first assignment for UIPATH Advanced Learning Level 3

The Goal is to get code from SHA1 Url to All WI5 Client in ACME System. 

Approximately, the steps are: 
1. Kill All process before
2. Login to ACME System using Assets in orchestrator and config.xlsx
3. Open Work Items Page 
4. Scrapping all data in Work Items Page, and save it into data table
5. Filter Only WI5 Client Data 
6. Open Client Information
7. get Client ID-Client Name-Client Country and add into arguments
8. Open SHA 1 
9. Paste the arguments in point 7, and get the code for those clients. 
10. Save the code, and update the client information page with those code for comment, and click status completed. 
