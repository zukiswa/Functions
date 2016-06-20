# Functions

You can think of 20 functions as small bite size programming challanges which aim to prepare coders to do Code Katas. Each coder will have to clone this repository and start to commit their implementation of the functions. A central CI instance will run their functions and give them a score for each function based on how many tests are passing. These functions are not to be completed on one sitting, but is to be completed on the coders own time.

> Fifty-three is the 16th prime number. It is also an Eisenstein prime, and a Sophie Germain prime. The sum of the first 20 primes is 5830, which is divisible by 20, a property shared by few other numbers.

You should:
* fork this repo
* link your forked copy of the repo to the upstream repo to get changes easily 
* To see how to do that have a look here: https://help.github.com/articles/syncing-a-fork/
* regularly update from upstream to check for changes
* use TDD
	* Always write the test code first - this will help you to understand what needs doing and get you in the habit of doing TDD. 
	* Write the first 5 functions using your own framework - the one you created in the Codex Setup project called TestMyCode
	* Once done get your code and test reviewed by your Tech Mentor (André)
	* Once the first 5 tests are passing start looking at [Qunit](http://qunitjs.com/)
		* Rewrite the tests for the first 5 functions using Qunit. 
	* From now on use Qunit to write all your tests
	* Setup a [Travis](https://travis-ci.org) and start monitoring your tests:
		* This will need a gulp setup - speak to your Tech Mentor about this
		
**commit to GIT regularly**

# These things count:
* regular commits
* testable code
* passing tests

# The functions

The function name and the file name should be the same

For example for hello.js the function should look like this:

```
function hello(){
	// your code goes here
}
```

Each function should have a test file called functionname_test.js

For ```hello.js``` it should be called ```hello_test.js```


> If any of these function specifications don't make sense, let's discuss, clarify and change it. 

Create a function that:

 #|File name & function name | Write a function that?
---|----------|-------------------------------------------------------------------------------------
1| hello.js | return "hello world"
2| hello_uppercase.js| takes a username as parameter and returns "Hello, < USERNAME parameter >!"
3| hello_joe.js | takes a username as parameter and returns as "Hello, < USERNAME parameter >!" if the username is Joe or Bob only say "Hello!"
4| number_list.js |takes a number as a parameter (n) and return a list of number from 1 to n
5| sum_numbers.js| takes a number as a parameter (n) and return the sum of numbers from 1 to n
6| length.js|takes a string parameter and return the length of the supplied parameter
7| upper.js |takes a string parameter and return the supplied parameter in uppercase
8 |reverse.js|takes a string parameter and return the reversed string parameter
9 |hello_list.js| takes a number as parameter and return a list of "hello world" entries equal to the number supplied
10 |high_low.js| given a list of numbers returns the highest and lowest numbers in the list
11 | count_words.js|takes a sentence as a parameter and return the number of words in the sentence
12 | sum_word_len.js |takes a sentence as a parameter and return the sum of the length of words in the sentence
13 | longest_word.js | takes a sentence as a parameter and return the longest word in the sentence and the length of the word
14|shortest_word.js|takes a sentence as a parameter and return the shortest word in the sentence and the length of the word
15|word_length.js|takes a sentence as a parameter and returns both the average word length rounded up & down
16|avg.js|takes a sentence as a parameter and return the average word length rounded up
17|start.js|takes a sentence as a parameter and return the letter most words starts with
18|ends.js|takes a sentence as a parameter and return the letter most words ends with
19|occurs_most.js|takes a sentence as a parameter and return the letter that occurs the most
20|occurs_least.js|takes a sentence as a parameter and return the letter that occurs the least

