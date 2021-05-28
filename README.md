# Defects

# 1.Title: Server Error is generated when proceeding to «Location Search» tab in navigation menu
Priority: High  
Severity: Critical  
Environment: Chrome Version 89.0.4389.90 (Official Build), (64-bit)  
Description:   
Steps to reproduce:
1.	Open https://www.wabashnational.com/ 
2.	Click on the «Location Search» tab in navigation menu (see attachment server error.jpg)
Actual result  
Server error is generated  

Expected result  
A page with corresponding information opens  

Additional Information  
Server Error is generated from every page of the site where navigation menu with «Location Search» tab is displayed.  



# 2.Title: The search function of the search field doesn’t generate any relevant result
Priority: High  
Severity: Major  
Environment: Chrome Version 89.0.4389.90 (Official Build), (64-bit)
Description: 
Steps to reproduce:
1.	Open https://www.wabashnational.com/ 
2.	Click on the search tool at the top right
3.	Type relevant query in the search box  
Actual result  
0 relevant result found  

Expected result  
The search shows all pages of the site with relevant information  
Searching of corresponding information on the site constantly returns 0 results on any request. The search box does not search for any query, which makes it difficult for the user to get required information. There is a lot of information in drop-down navigation menu. Therefore, for better and easier search it is necessary to have working internal search-box.  


Additional information  
The search bar shows tip «no data found» when starting typing any letter, world etc. Even if the query is related directly to the site information.  



# 3.Title: Submission of «How can we help?» form with filling no data
Priority: High  
Severity: Critical  
Environment: Chrome Version 89.0.4389.90 (Official Build), (64-bit)  
Description:   
Steps to reproduce:  
1.	Open https://www.wabashnational.com/we-are-wabash/heritage 
2.	Scroll to the bottom of the page
3.	Leave all the fields empty and click the «Submit» button  

Actual result  
The form is successfully accepted.  

Expected result  
The mandatory fields should be indicated. No submission with blank mandatory fields.   

The form «How can we help?» allows the user to fill no data and submit application. Generally every form has mandatory fields to fill in which are indicated with asterics sign or tooltip. There is no common sense in allowing the user to submit the form without any information.   



# 4.Title: Search radius slider on Location tab doesn’t react to any changing distance actions 
Priority: High  
Severity: Major  
Environment: Chrome Version 89.0.4389.90 (Official Build), (64-bit)  
Description:   
Steps to reproduce:  
1.	Open https://www.wabashnational.com/location-search/results
2.	Click on search radius slider   

Actual result  
Search radius slider doesn’t move  

Expected result  
Search radius slider can be moved for further distance changing and showing the actual mile radius.  
