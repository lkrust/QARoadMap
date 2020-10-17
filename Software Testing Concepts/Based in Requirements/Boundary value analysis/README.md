# Software Testing concepts > Based in Requirements >  Bounday value analysis

## Texts:

- [ ] [Wikipedia](https://en.wikipedia.org/wiki/Boundary-value_analysis)
- [ ] [softwaretestinghelp](https://www.softwaretestinghelp.com/what-is-boundary-value-analysis-and-equivalence-partitioning/)


## Exercises:

### 1. A particular text field accepts only alpha characters. Which of the following is invalid Equivalence Partition?

	a. APPLE
	b. apple
	c. aPPle
	d. a2pple

<Details>
	<summary>Answer</summary>
	d
</Details>


### 2. A Online Bus Reservation System asks number of seats to be reserved by user where user can reserve seats till its capacity will be full. If a tester wants to test that particular field using Boundary Value, what do you think will be a correct set of input values?

	a. 1, 2, capacity -1, capacity, capacity + 1
	b. 0, 1, capacity, capacity + 1
	c. 0, 1, 2, capacity + 1, a very large number
	d. 0, 1, 10, 100, capacity, capacity+1

<Details>
	<summary>Answer</summary>
	b
</Details>


### 3. The speedometer of a car uses 7 colours to show the speed. Each colour covers a range of 20 km, with an operating minimum and maximum of 0 and 140. Which of the following values is LEAST likely to have been identified when applying the Boundary Value Test Design Technique?

	a. -1
	b. 0
	c. 7
	d. 121

<Details>
	<summary>Answer</summary>
	c
</Details>


### 4. To pass an Exam, a candidate has to score minimum of 50 marks in order to clear the exam. The maximum that he can score is 100 marks. Identify the Valid Equivalence values if the student passes the exam.

	a. 50, 58, 75
	b. 49, 50, 51
	c. 52, 60, 99
	d. 0, 15, 50

<Details>
	<summary>Answer</summary>
	c
</Details>


### 5. Which of the following values for age are in the same Equivalence Partition?

- If you are less than 18, you are too young to be registered for program.
- Between 18 and 50 inclusive, you will receive a 20% discount.
- Anyone over 50 is not eligible for a discount.

	a. 17, 18, 19
	b. 51, 52, 53
	c. 18, 49, 50
	d. 17, 49, 51

<Details>
	<summary>Answer</summary>
	b
</Details>


### 6. Equivalence partitioning and boundary value analysis techniques are used only during system testing.

	a. True
	b. False

<Details>
	<summary>Answer</summary>
	b
</Details>


### 7. A city field in software accepts 3 to 25 alpha characters only. Using BVA technique what will be the possible number of combinations?

	a. 3, 4, 24, 25
	b. 2, 3, 25, 26
	c. 2, 3, 24, 25
	d. 3, 5, 25, 26

<Details>
	<summary>Answer</summary>
	b
</Details>


### 8. Which of the followings is/are not a Specification Based Technique?

	a. Cause-Effect Table
	b. State transition Testing
	c. Decision Coverage
	d. Use case Testing

<Details>
	<summary>Answer</summary>
	c
</Details>


### 9. A theme park charges entry fee based on age group. For children below 3 it charges nothing, for 3-10 it charges Rs. 500/-, for 10-18 it charges Rs. 800/-,then for 18-60 it charges Rs. 1000/- and above 60 it charges Rs. 500/- again. Using Boundary Value Analysis, what will be the values to test if person pays Rs. 500/- entry fee?

	a. 0,2,3
	b. 2,3,10,11,59,60,100,102
	c. 2,3,10,11,59,60,100,101
	d. 59,60,100,101

<Details>
	<summary>Answer</summary>
	c
</Details>


### 10. What is an Equivalence Partition?

	a. A set of test cases for testing classes of objects.
	b. An input or output range of values such as have only one value in the range becomes a test case.
	c. An input or output range of values such that each value in the range becomes a test case
	d. An input or output range of values such that every tenth value in the range becomes a test case.

<Details>
	<summary>Answer</summary>
	b
</Details>


### 11. Which is/are the characteristics of Equivalence Partitioning?

	a. In equivalence-partitioning technique we need to test only one condition from each partition.
	b. If one condition in a partition works, we assume all of the conditions in that partition will work.
	c. if one of the conditions in a partition does not work, then we assume that none of the conditions in that partition will work.
	d. Equivalence partitions and equivalence classes both terms mean exactly the same thing.
	e. All of the above

<Details>
	<summary>Answer</summary>
	e
</Details>
