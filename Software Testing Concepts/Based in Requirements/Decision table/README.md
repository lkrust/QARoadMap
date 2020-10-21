# Software Testing concepts > Based in Requirements >  Decision Table

## Texts:

- [ ] [Wikipedia](https://en.wikipedia.org/wiki/Decision_table)
- [ ] [reqtest](https://reqtest.com/requirements-blog/a-guide-to-using-decision-tables/#:~:text=A%20decision%20table%20is%20an,used%20to%20model%20complicated%20logic.)


## Exercises:

### 1. Construct a decision table for the following piece of Lenton local knowledge:
When a burglar alarm sounds, if it is in one of students’ houses where alarm sounds every week, ignore it. Otherwise have a look outside and if the house looks not broken into and there is nobody moving inside it, ignore the alarm. Otherwise call police.
	List the resulting rules.

<Details>
	<summary>Answer</summary>
	
/ | Rule 1 | Rule 2 | Rule 3
------------ | ------------- | ------------- | -------------
One of those houses | Y | N | N
Suspicious activity | / | N | N
------------ | ------------- | ------------- | -------------
Ignore | X | X | /
Call police | / | / | X
	
	Resulting rules:
	- Rule 1: if one of those houses then ignore
	- Rule 2: if not one of those houses and not suspicious activity then ignore
	- Rule 3: if not one of those houses and suspicious activity then call police
		Note: rule 2 will work just as well if skip the first check:
	- Rule 2: if not suspicious activity then ignore
</Details>

