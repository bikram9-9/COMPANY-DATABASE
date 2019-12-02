# COMPANY-DATABASE
I have created a database for a Company XYZ, which purchases some parts from vendors to product products. 
It has several departments, marketing sites, and parts supply vendors in the company.


There is an XYZ Company, which purchases some parts from vendors to produce some products. It has several departments, marketing sites, and parts supply vendors in the company. 
1) For each department, department id and department name will be recorded. 
2) People in the company can be divided into three types -- employees, customers, and potential employees. Each person can belong to more than one type. Each person in the company has the following attributes: Personal_ID, Name (Last Name, First Name), Age (below 65), Gender, Address (address line 1, address line 2, city, state, zipcode), and Phone number (one individual may have more than one phone number). For customers, his/her preferred salesmen were recorded in the system. For employees, Rank and Title (e.g. CEO, Principle, Partner, etc.) will be recorded for them. 
3) Each employee of the company must have only one direct supervisor, while each supervisor can have several supervisees. One employee can work for one or more departments at different time. But at one time, one employee can only work for one department. The system needs to record start time and end time for each shift among different department for one employee. 
4) Each job position’s information is recorded to hire new people. It contains the Job ID, job description, and posted date in the system. 
5) The job positions are posted by the departments. Both existing employees and potential employees can apply each job post by any department. The company will select some candidates from the applications and make interviews. 
6) For each job position, several interviews will be made to select a suitable person. 
7) For each interview, candidates (interviewees), interviewers, job position and interview time are recorded. After each round interview, the interviewers give a grade to it ranging from 0 to 100. The grade over 60 represents that the interviewee pass the interview. One person is selected when her/his average grade is over 70 and she/he passes at least 5 rounds of interviews. 
8) For each product in the company, the system needs to record Product ID, Product Type, Size, List Price, Weight, and Style. 
9) There are many marketing sites for the company. For each site, Site ID, Site Name, and Site Location are recorded. 
10) There are several people working for each site, and meanwhile, one person can work on different sites. It is able to track the details of each sale history --- salesmen, customers, product, sale time, and sites. 
11) Part purchase is also a vital activity in the company. The system needs to record each vendor’s Vendor ID, Name, Address, Account Number, Credit Rating, and Purchasing Web Service URL. 
12) One vendor may supply many types of parts. The price of the same part type may vary from different vendors but the price of one part type of one vendor will keep same. It is able to track which part types used in each product and the number of each type of part used for the product. 
13) In addition, the system maintains the information of each employee’s monthly salary which includes transaction number, pay_date, and amount (Note: transaction number could be same among different employees. However, for each employee, the transaction number is unique). 

