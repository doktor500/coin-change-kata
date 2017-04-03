### What is a kata?

A code kata is an exercise in programming which helps a programmer improve their skills through practice and repetition

### Which kata are we solving?

We are going to solve the **Coin change kata**

The coin change kata exercise should produce the minimal amount of change for a given amount

For instance, If the input is: 99 cents of a dollar, the output should be: 3 quarters, 2 dimes, and 4 pennies
The output can be something as simple as `25, 25, 25, 10, 10, 1, 1, 1, 1` which is the same as 99 cents

The currency unit that we will use, will be 1 cent, instead of 1 dollar

### 3 Rules of TDD to have in mind for solving the exercise

1. You are not allowed to write any production code unless it is to make a failing unit test pass
2. You are not allowed to write any more of a unit test than is sufficient to fail
3. You are not allowed to write any more production code than is sufficient to pass the one failing unit test

### Setup the project

Import the project as a Gradle or Maven project on IntelliJ/Eclipse

### Gradle + Eclipse setup

If you are using Gradle and Eclipse, set the Gradle user home directory the directory to the path in where the project has been cloned


![Configuration](https://github.com/doktor500/coin-change-kata/blob/master/config.png)
