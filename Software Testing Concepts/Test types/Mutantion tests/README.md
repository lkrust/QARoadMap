# Software Testing concepts > Test types > Mutation test

## Texts:

- [ ] [wikipedia](https://en.wikipedia.org/wiki/Mutation_testing)
- [ ] [dev](https://dev.to/schreiber_chris/mutation-testing-in-1000-characters-193a)
- [ ] [State of Mutant testing at google](https://research.google/pubs/pub46584/)


## Exercises:


### 1. What is Mutant Testing?

<Details>
	<summary>Answer</summary>
	Mutant tests are, in a nutshel, test of tests. Code coverage has it's usage, but doesn't determine if tests are really testing what should be tested or the quality of the tests. Mutant tests create multple copies of the code base with small mutations(one mutation per test suite run) and run the entire suite against this mutation. if all tests passes the mutant is killed and the tool will go to the next mutation.
</Details>

### 2. What are the cons of Mutant Testing:

<Details>
	<summary>Answer</summary>
	<br>- Very slow. If your suite takes 1 minute to run and you have 60 mutants(which is not much), it will take 60minutes to execute
  <br>- Demands some knowledge on the code base
  <br>- Demands some knowledge on the tool and concept
</Details>

### 3. Give 5 example of mutants

<Details>
	<summary>Answer</summary>
	<br>- inversion of conditions
  <br>- change boundary conditions (< becomes <=)
  <br>- change incrementation of counters
  <br>- change mathematical operators
  <br>- return null instead of returned value
</Details>

### 4. Give 5 example of mutant testing tools:

<Details>
	<summary>Answer</summary>
	<br>- JS - stryker-mutator.io
  <br>- Java - https://pitest.org/
  <br>- Python - https://pypi.org/project/MutPy/
  <br>- Ruby - https://github.com/mbj/mutant
  <br>- PHP - https://infection.github.io/guide/
</Details>
