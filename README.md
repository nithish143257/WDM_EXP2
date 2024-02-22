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

<img width="348" alt="image" src="https://github.com/Nagadurg/WDM_EXP2/assets/94185707/53fa0aa1-6f3d-467c-aa60-069a38626fbf">

Training Data Set -> Banking Table

<img width="359" alt="image" src="https://github.com/Nagadurg/WDM_EXP2/assets/94185707/ba0d1a01-a0f0-456e-8c87-946440cdb76f">

Training Data Set -> Employee Table

<img width="221" alt="image" src="https://github.com/Nagadurg/WDM_EXP2/assets/94185707/a645a647-6fbf-4afc-a4b2-019f8f2dbe27">

### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:

Buying Table
<img width="689" alt="image" src="https://github.com/Nagadurg/WDM_EXP2/assets/94185707/f603ef53-f03a-4e1d-ae95-d5611d5f1a67">

Banking Table

<img width="644" alt="image" src="https://github.com/Nagadurg/WDM_EXP2/assets/94185707/ed60639c-f00a-4648-8b53-fa04299d7c33">

Employee Table

<img width="583" alt="image" src="https://github.com/Nagadurg/WDM_EXP2/assets/94185707/55f35af5-60dd-4716-85e6-fc7f5278783b">


### RESULT: Thus this program has been successfully executed.
