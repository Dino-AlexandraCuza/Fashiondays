# Fashiondays
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: Fashiondays.ro

![fashion days logare 1](https://github.com/Dino-AlexandraCuza/Fashiondays/assets/167756289/6145432f-88eb-4b27-baea-a3aff6d76579)


Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories:How to create a user account,Various scenarios for applying filters, were created in Jira and describes the functional specifications , for which the final project is performed upon.


![primu story](https://github.com/Dino-AlexandraCuza/Fashiondays/assets/167756289/b9891c93-e17f-4e70-9e0b-08eae8b5de0d)

![story doi](https://github.com/Dino-AlexandraCuza/Fashiondays/assets/167756289/19e028fd-c8c3-4cd7-86c6-4580184072e5)


 The plan identifies the items to be tested, the features to be tested, the types.

<h4>1.1. Roles asigned to the project and persons allocated</h4>

Cuza Alexandra, Andrei Popescu, Elena Ionescu, Mihai Vasile
<ul>
  <li>Project manager</li> 
  <li>Product owner</li>
 
 The testing process will be executed based on the application requirements. 


 1.1.1 Entry criteria defined
-ensuring that the test plan will be finished
-all risk project were mitigated and identified

1.1.2 Exit criteria defined
-the regresion testing is finished
-the bugs were identified and fixed
-the level of execution tests was achieved

1.1.3 Test scope
Tests in scope:
The tests are main focused on the creation of new account and the filters.  

1.1.4Tests not in scope:
Tests that are in the security and progression range are not covered.

1.1.5 Risks detected
Project risks:
Project risks includes security risks  for the instabilty of password account managing.

1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.



**1.2 Test Analysis**

The testing process will be executed based on the application requirements.

The following test conditions were found:<br>

1. The new user should  be  able to create the account by introducing a valid e-mail
2. Verify that the new user should not be able to create a password only with special characters
3. Verify that the new user should not  be able to create  an account with an already taken e-mail
4. Verify that the new user should be able to create a password with alphanumeric characters
5. Verify that the user can access a masculine pink colour t-shirt with 2 filters: pink and multicolour
6. Verify that the user can access a masculine black sport  t-shirt : using filters-colour and sport
7. Verify that the user can add the t-shirt wanted to "Favorites"
8. Verify that the user can use all filters on Casio watches- even if the selected  watch was searched or accessed by main Casio filter in the main list of products
9. Verify that the user can acces a yellow t-shirt, without sleeves, and filtered  by "New collection"
10. Verify that the user can not access a pair of shoes  which are out of stoc


<h3>1.3 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here:[Test Cases](https://github.com/user-attachments/files/15860365/test_cases.1.xlsx)


<h3>1.4 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:
login user/creating new account and verify that the filters are up to be used in any situation

<h3>1.5 Test Execution </h3>

Test cases are executed on the created test Cycle summary: Fashiondays

Bugs have been created based on the failed tests. The complete bug reports can be found here:
The following is a summary of the bugs that have been found
User can access a masculine pink colour t-shirt with 2 filters: pink and multicolour
Verify that the user can use all filters on Casio watches- even if the selected watch was searched or accessed by main Casio filter in the main list of products 
The user shouldn't be able to create an account with only special characters password

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

**1.6 Test Completion**

As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here:

![trasa3](https://github.com/Dino-AlexandraCuza/Fashiondays/assets/167756289/e6b6f74e-d882-442f-a12e-098592a89a55)



![trasa4](https://github.com/Dino-AlexandraCuza/Fashiondays/assets/167756289/e4f0ed4a-9ce8-4e26-b4af-473e31b79678)



The traceability matrix was generated and can be found here: [Traceability matrix](https://itfclasses.atlassian.net/projects/PTAC?selectedItem=com.thed.zephyr.je__traceability-project-level)

Test execution chart was generated and can be found below. 
[Test Execution chart](https://itfclasses.atlassian.net/jira/dashboards/1037)
![image](https://github.com/Dino-AlexandraCuza/Fashiondays/assets/167756289/85eb706d-7f2e-4f26-90e9-4482af6bb0da)

The final report shows that a number 10 tests have failed of a total of 3.
A number of 3 total bugs were found, from which the priority is: one high and two medium.

The tests that ran for this application have suggested that the security of the app can be improved by adding some  limits to the password -maximum of characters, upper or lower cases, alplanumeric combined with special characters, for making the password unique and stronger. The filter section can be improved and in the future to run for all products equally in any form of product search.
