### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 27 - 02 - 2025
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
### EMPLOYEE TABLE

![image](https://github.com/R-Udayakumar/WDM_EXP2/assets/118708024/599f50d1-c216-4477-bd88-1c6bd3210584)

### BANK TABLE
![Screenshot 2024-02-29 131905](https://github.com/R-Udayakumar/WDM_EXP2/assets/118708024/c6795c4b-5788-4257-8913-5592a74c6267)

### BUYING TABLE
![image](https://github.com/R-Udayakumar/WDM_EXP2/assets/118708024/21e22e88-c60e-4b5a-969d-35b2674c6a7e)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
### EMPLOYEE TABLE
![Screenshot 2024-02-15 134918](https://github.com/R-Udayakumar/WDM_EXP2/assets/118708024/d6e3f7ff-7648-40af-8886-164520874bd4)

### BANK TABLE
![Screenshot 2024-02-29 131923](https://github.com/R-Udayakumar/WDM_EXP2/assets/118708024/cd0489ca-b0ff-4070-bf52-60d03f38786a)

### BUYING TABLE
![Screenshot 2024-02-15 135146](https://github.com/R-Udayakumar/WDM_EXP2/assets/118708024/d45e501f-071d-45f8-af0e-e2fc0a5ba392)

### RESULT: 
Thus the program for Generating Association Rules for Employee dataset using Apriori Algorithm has been accomplished successfully.
