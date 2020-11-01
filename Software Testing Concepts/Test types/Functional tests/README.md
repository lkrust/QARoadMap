# Software Testing concepts > Test types > Functional Test

## Texts:

- [ ] [mabl](https://www.mabl.com/functional-testing)
- [ ] [simform](https://www.simform.com/functional-testing/)


## Exercises:

### 1. What do you understand by the term ‘Functional testing’?

<Details>
	<summary>Answer</summary>
	A black box testing technique, where the functionality of an application is tested to generate the desired output by providing certain input is called ‘Functional testing’.

	The role of functional testing is not only to validate the behavior of the application as per the requirement document specification but is also to verify whether the application is ready to be released into the live environment or not.

	Given below are a few functional testing techniques that are commonly used:

	- Unit testing
	- Smoke testing
	- Integration testing
	- System testing
	- Usability testing
	- Regression testing
	- User Acceptance testing
</Details>

### 2. What are the important steps that are covered in Functional testing?

<Details>
	<summary>Answer</summary>
	Following are the steps that should be covered as a part of functional testing:

	- Understanding the Requirement document specification and clearing the doubts and queries in the form of review comments.
	- Writing the test cases with respect to the requirement specification by keeping in mind all the scenarios that should be considered for all the cases.
	- Identifying the test inputs and requesting the test data that is required to execute the test cases as well as to check the functionality of the application.
	- Determine the actual outcomes as per the input values to be tested.
	- Execute the test cases that determine whether application behavior is as expected or any defect has occurred.
	- Compare the actual result and the computed result to find out the actual outcome.
	- Compare
</Details>

### 3. Explain the difference between Functional testing and Non-Functional testing.

<Details>
	<summary>Answer</summary>
	The difference between Functional testing and Non-functional testing can be explained as below:

	Functional Testing	NonFunctional Testing
	Functional testing is performed to determine the system behaviour as per the client functional requirements.	Non-functional testing is the process to determine the system performance as per client expectations
	Functional testing is performed first with the help of Manual and Automation testing tools.	Non-functional testing is performed after functional testing with the effective tools required.
	It is easy to perform manual testing as client requirements are the input in functional testing.	It is difficult to perform manual testing as scalability, reliability, speed and other performance parameters are input in non functional testing.
	Functional testing is of following types:
	- Unit Testing
	- Smoke Testing
	- Sanity Testing
	- Integration testing
	- User Acceptance testing
	- Regression testing	Non-functional testing is of following types:
	- Performance testing
	- Load, Stress, Volume Testing
	- Security testing
• Compatibility testing
</Details>

### 4. For any Web Application, what are the possible login features that should be tested?

<Details>
	<summary>Answer</summary>
	- Check the input fields i.e. Username and password with both valid and invalid values.
	- Try entering valid email id with an incorrect password and also enter an invalid email and valid password. Check for the proper error message displayed.
	- Enter valid credentials and get logged in to the application. Close and reopen the browser to check if still logged in.
	- Enter the application after logging in and then again navigate back to the login page to check whether the user is asked again to log in or not.
	- Sign in from one browser and open the application from another browser to verify whether you are logged into another browser also or not.
	- Change password after logging into the application and then try to login with that old password.
	- There are few other possible scenarios as well which can be tested.
</Details>


### 5. Explain the difference between Severity and Priority.


<Details>
	<summary>Answer</summary>
	Defect Severity is defined by the level or the degree of impact by the defect on the application under test. Higher the severity of the defect, the more is the impact on the application.

	Following are the 4 classes in which a defect severity is categorized:
	- Critical
	- Major
	- Medium
	- Low
	- Defect priority defines the order in which the defect should be resolved first i.e. the higher the priority of the defect implies that the application is unusable or stuck at some point and the defect should be resolved as soon as possible.
</Details>


### 6. When do we perform Smoke testing?

<Details>
	<summary>Answer</summary>
	Smoke testing is performed on the application after receiving the build. Tester usually tests for the critical path and not the functionality in deep to make sure, whether the build is to be accepted for further testing or to be rejected in case of broken application.

	A smoke checklist usually contains the critical path of the application without which an application is blocked.
</Details>


### 7. What do you understand by Sanity testing?

<Details>
	<summary>Answer</summary>
	Sanity testing is performed after receiving the build to check the new functionality/defects to be fixed. In this form of testing the goal is to check the functionality roughly as expected and determine whether the bug is fixed and also the effect of the fixed bug on the application under test.

	There is no point in accepting the build by the tester and wasting time if Sanity testing fails.
</Details>


### 8. What do you understand by Requirement Traceability Matrix?

<Details>
	<summary>Answer</summary>
	Requirement Traceability Matrix (RTM) is a tool to keep a track of requirement coverage over the process of testing.

	In RTM, all requirements are categorized as their development in course of sprint and their respective ids (new feature implementation/ enhancement/ previous issues, etc) are maintained for keeping a track that everything mentioned in the requirement document has been implemented before the release of the product.

	RTM is created as soon as the requirement document is received and is maintained until the release of the product.
</Details>