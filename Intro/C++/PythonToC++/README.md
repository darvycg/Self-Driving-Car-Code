# Python to C++
This Project has the Histogram Filter previously built in Python 3 ported over to C++. The program uses a belief system where it creates a 2D Grid and initializes all beliefs to a normalized value. After it senses its surroundings, it updated the probability of its location after some calculations. Every iteration that it senses will increase its confidence of its location.
## Installation
Download the repo. After you have a local copy, you can run the following command after having MinGW installed:
```
g++ -std=c++11 tests.cpp
```
This works best when using a UNIX based system.

## Running the Program
Simply run the executable built from the previous step. You should also be able to change the name of the executable by running the following instead:
```
g++ -std=c++11 tests.cpp tests.exe
```
The default name will be `a.exe` for windows and `a.out` for UNIX based systems.

To run the program from command line, type:
```
./a.exe
```
or for UNIX
```
./a.out
```

## Known Errors
There is a compile error that I received plenty of times regarding the overload of `show_grid` method. To fix this issue, I ended up compiling with CLion. Another tell-tale is receiving the following error:

![alt text](https://github.com/darvycg/Self-Driving-Car-Code/blob/master/Intro/C%2B%2B/PythonToC%2B%2B/images/Error.PNG "Error Running Program") 

## Disclaimer
Not all code was written by me as some was provided by the class. 
