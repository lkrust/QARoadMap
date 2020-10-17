# Software Testing concepts > Based in Requirements >  Equivalence Partitioning

## Texts:

- [ ] [Wikipedia](https://en.wikipedia.org/wiki/Equivalence_partitioning#:~:text=Equivalence%20partitioning%20or%20equivalence%20class,each%20partition%20at%20least%20once.)
- [ ] [ToolsQA](https://www.toolsqa.com/software-testing/istqb/equivalence-partitioning/)


## Exercises:

### 1. What is an equivalence partition (also known as an equivalence class)?

	a. A set of test cases for testing classes of objects.
	b. An input or output range of values such that only one value in the range becomes a test case.
	c. An input or output range of values such that each value in the range becomes a test case.
	d. An input or output range of values such that every tenth value in the range becomes a test case.

<Details>
	<summary>Answer</summary>
	b
</Details>


### 2. One of the fields on a form contains a text box which accepts numeric values in the range of 18 to 25.
Indentify the invalid Equivalence class

	a. 17
	b. 19
	c. 24
	d. 21

<Details>
	<summary>Answer</summary>
	a
</Details>


### 3. In a Examination a candidate has to score minimum of 24 marks inorder to clear the exam. The maximum that he can score is 40 marks. Identify the Valid Equivalence values if the student clears the exam.

	a. 22,23,26
	b. 21,39,40
	c. 29,30,31
	d. 0,15,22

<Details>
	<summary>Answer</summary>
	c
</Details>


### 4. One of the fields on a form contains a text box which accepts alpha numeric values. Identify the Valid equivalence class

	a. BOOK
	b. Book
	c. Boo01k
	d. book

<Details>
	<summary>Answer</summary>
	c
</Details>


### 5. The Switch is switched off once the temperature falls below 18 and then it is turned on when the temperature is more than 21. When the temperature is more than 21. Identify the Equivalence values which belong to the same class.

	a. 12,16,22
	b. 24,27,17
	c. 22,23,24
	d. 14,15,19

<Details>
	<summary>Answer</summary>
	c
</Details>


### 6. A program validates a numeric field as follows: 
values less than 10 are rejected, values between 10 and 21 are accepted, values greater than or equal to 22 are rejected. which of the following input values cover all of the equivalence partitions?

	a. 10,11,21
	b. 3,20,21
	c. 3,10,22
	d. 10,21,22

<Details>
	<summary>Answer</summary>
	a
</Details>


### 7. The specification: an integer field shall contain values from and including 1 to and including 12 (number of the month). Which equivalence class partitioning is correct?

	a. Less than 1, 1 through 12, larger than 12
	b. Less than 1, 1 through 11, larger than 12
	c. Less than 0, 1 through 12, larger than 12
	d. Less than 1, 1 through 11, and above

<Details>
	<summary>Answer</summary>
	a
</Details>


### 8. A program validates a numeric field as follows: values less than 10 are rejected, values between 10 and 21 are accepted, values greater than or equal to 22 are rejected. Which of the following covers the MOST boundary values?

	a. 9,10,11,22
	b. 9,10,21,22
	c. 10,11,21,22
	d. 10,11,20,21

<Details>
	<summary>Answer</summary>
	b
</Details>


### 9. In a system designed to work out the tax to be paid:
An employee has £4000 of salary tax free. The next £1500 is taxed at 10%. The next £28000 is taxed at 22%. Any further amount is taxed at 40%. Which of these groups of numbers would fall into the same equivalence class?

	a. £4800; £14000; £28000
	b. £5200; £5500; £28000
	c. £28001; £32000; £35000
	d. £5800; £28000; £32000

<Details>
	<summary>Answer</summary>
	d
</Details>


### 10. Order numbers on a stock control system can range between 10000 and 99999 inclusive. Which of the following inputs might be a result of designing tests for only valid equivalence classes and valid boundaries:

	a. 1000, 5000, 99999
	b. 9999, 50000, 100000
	c. 10000, 50000, 99999
	d. 10000, 99999
	e. 9999, 10000, 50000, 99999, 10000

<Details>
	<summary>Answer</summary>
	c
</Details>


### 11. Equivalence partitioning is:

	a. A black box testing technique used only by developers
	b. A black box testing technique than can only be used during system testing
	c. A black box testing technique appropriate to all levels of testing
	d. A white box testing technique appropriate for component testing

<Details>
	<summary>Answer</summary>
	c
</Details>


### 12. Which of the following is a valid collection of equivalence classes for the following problem: An integer field shall contain values from and including 1 to and including 15

	a. Less than 1, 1 through 15, more than 15
	b. Negative numbers, 1 through 15, above 15
	c. Less than 1, 1 through 14, more than 15
	d. Less than 0, 1 through 14, 15 and more

<Details>
	<summary>Answer</summary>
	a
</Details>


### 13. Which of the following is a valid collection of equivalence classes for the following problem: Paying with credit cards shall be possible with Visa, Master and Amex cards only.

	a. Visa, Master, Amex;
	b. Visa, Master, Amex, Diners, Keycards, and other option
	c. Visa, Master, Amex, any other card, no card
	d. No card, other cards, any of Visa – Master – Amex

<Details>
	<summary>Answer</summary>
	d
</Details>


### 14. Given the following specification, which of the following values for age are in the SAME equivalence partition? If you are less than 18, you are too young to be insured. Between 18 and 30 inclusive, you will receive a 20% discount. Anyone over 30 is not eligible for a discount.

	a. 17, 18, 19.
	b. 29, 30, 31.
	c. 18, 29, 30.
	d. 17, 29, 31.

<Details>
	<summary>Answer</summary>
	c
</Details>

### 15. One of the fields on a form contains a text box which accepts alphabets in lower or upper case.Indentify the invalid Equivalence class value.

	a. CLASS
	b. cLASS
	c. CLass
	d. CLa01ss

<Details>
	<summary>Answer</summary>
	d
</Details>
