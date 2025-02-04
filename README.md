# Cpp-Module-00
Namespaces, classes, member functions, stdio streams, initialization lists, static, const, and some other basic stuff

## ex00 [Megaphone](https://github.com/dhuss42/Cpp-Module-00-04/blob/main/ex00/megaphone.cpp)

A Program that changes the lower-case characters of the input string into upper-case characters.
If no string is passed as an argument the program outputs "* LOUD AND UNBEARABLE FEEDBACK NOISE *"

## ex01 [Phonebook](https://github.com/dhuss42/Cpp-Module-00-04/blob/main/ex01/main.cpp)

A Program that simulates a small phonebook in which we can add up to eight different contacts and search for specific contacts.

Entering ADD prompts the user to input certain information. This information is then stored in an array of eight contacts. The oldest are overwritten as soon as there are more than eight contacts added.

Entering SEARCH prints a list of all contacts and propts the user to enter a valid index. The contact at index i is then retirved and the information printed. The information is aligned right and truncated if it exceeds ten characters

Entering EXIT exits the program

## ex02 [Lost File](https://github.com/dhuss42/Cpp-Module-00-04/blob/main/ex02/Account.cpp)

In this exercise we had to recreate the "lost" Account.cpp file based on log file a tests.cpp and an Account.hpp file.

I first made comments for all the unfamiliar information and researched their functionality. Then I compared the order of the output from the logfile with the order of the functions beeing called. Next, I made notes on what these functions were supposed to do. Finally, I recreated the functions, based on their prototypes and the information I had gathered.

