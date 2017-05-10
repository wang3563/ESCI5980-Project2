# ESCI5980-Project2
For the second project of ESCI5980, I created the Ucalculation class, which incorporated the isofilter class that was written for project1. The purpose of Ucalculation class is to filter and manipulate data from existing data files in order to do certain calculations. The specific data files that are compatible with the Ucalculation class are generated in the University of Minnesota's Trace Metal Isotope Geochemistry Laboratory. This is part of an ongoing project which aims to turn the existing calculations performed by the excel sheet using methods written in Macros by Hai Cheng. The specific uses and instantiations would be vividly demonstrated by the final project in which it is partly incorperated. 
To use Ucalculation class,simply change current directory to the directory in which the Ucalculation.py file and specific files that are named u.xlsm and Th.xlsm are stored in. The two excel files are examples of files generated in the lab, hence my program is designed arround them.

## Demo
An exmple of how Ucalculation.py is ran should be demonstrated clearly with example below. 

The Following input prompts would appear on the command line after calling main() for Ucalculation.py to run
```
What spike did you use? Options: DIII-B, DIII-A, 1I, 1H : DIII-B
```
Enter DIII-B

```

Would you like to print as you go? [y/n] : 
```
Enter y
```
What is your abundant sensitivity of 238U - 237U ? 6E-7
```
Enter 6E-7
```
what is your abundant sensitivity of 229U - 230U ? 4.67E-7
```
Enter 4.67E-7
```
Enter the source file name to filter for U: 
```
Enter U.xlsm

```
Enter the file name to filter for Th: 
```
Enter Th.xlsm
