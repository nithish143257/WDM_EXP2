### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE:21/2/23
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:

Training Data Set -> Buying Table

![image](https://github.com/nithish143257/WDM_EXP2/assets/113762839/13606479-2e67-4fef-b0d2-9f31c438ca6a)

Training Data Set -> Banking Table

![image](https://github.com/nithish143257/WDM_EXP2/assets/113762839/b2a86230-3c3c-4ca2-9eb5-4757a3bcd1c6)

Training Data Set -> Employee Table

![image](https://github.com/nithish143257/WDM_EXP2/assets/113762839/4956d4e4-ebce-4a13-8c40-26aa47eba2a2)

### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:

Buying Table

![image](https://github.com/nithish143257/WDM_EXP2/assets/113762839/43bafe01-5f6d-4934-88e5-4a0d85e7d370)

Banking Table

![image](https://github.com/nithish143257/WDM_EXP2/assets/113762839/e6d0a2b0-db90-46ad-9bc1-a8a9bfba9904)

Employee Table

![image](https://github.com/nithish143257/WDM_EXP2/assets/113762839/d29e887d-6a51-4543-a5aa-814d51e76ab0)


### RESULT: Thus this program has been successfully executed.
