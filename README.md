# hw4 Tester
## LAST UPDATE: 2022-03-20 20:50
* Fixed Q5 test, case3 & case4. @Jonathan Yahav
## PREVIOUS UPDATE: 2022-03-19 19:15
* Added instructions regarding how to execute the program on nova with the new package hierarchy that we didn't have until this HW.

### How to run on nova?
1. Clone your project as usual.
2. Go inside the deepest folder (`ex4`) using `cd` command.
3. Run `javac *.java`.
4. Go back to `src` folder (be inside it).
> * You can go back one folder at a time using `cd ..`.
> * Why `src` folder? If you'll notice there is a line `package il.ac.tau.cs.sw1.ex4;` on top of our files.
> * When you run `ls` the output should be `il`.
5. Run `java il.ac.tau.cs.sw1.ex4.WordPuzzleTester`.

### General notes:
1. I encountered many "grey areas" from reading the instructions and I didn't know for sure if I can assume the input is valid or not, so I've added "Lechomra" tests.
2. If you find mistakes, please let me know and I'll fix them.
3. If you think of tests that check uncovered parts, send them to me and I'll add it here, credit will be given below.

#### Additional contributors:
* Jonathan Yahav
