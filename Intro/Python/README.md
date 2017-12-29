# Histogram Filter
This python code runs a histogram filter to close in on a randomized location using a cycle of sensing and prediction.
## Installing Program
Ensure you have matplotlib installed. If it is not installed, run the following:
```
python -mpip install -U matplotlib
```
## Running Program
Simply type the following:
```
python main_hisogram_filter.python
```
This will open a window with the beliefs before attempting to predict the location. It should look something like this (with the red star being in a random location everytime)

![alt text](https://github.com/darvycg/Self-Driving-Car-Code/blob/master/Intro/Python/images/HistogramFilter/First_Belief.png "First Belief")

After closing the initial plotting window, the program will simulate 100 steps and show a new plot that would look something like this (star will have changed locations):

![alt text](https://github.com/darvycg/Self-Driving-Car-Code/blob/master/Intro/Python/images/HistogramFilter/Last_Belief.png "Last Belief")

## Future Improvements
Add console input for the number of steps for the user to input