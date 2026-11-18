### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm.
### NAME : ASHRATHI S
### DATE: 18-11-2026
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
@relation MarketBasket

@attribute Bread {t,f}
@attribute Butter {t,f}
@attribute Milk {t,f}

@data
t,t,t
t,t,f
t,f,t
t,t,t
t,f,t
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6ff32c78-ed22-4f17-ae69-2557eb31625e" />



### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/428398ac-4175-42a1-b96e-8b572dce019c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/64896ef2-e262-47c7-bb4e-23d6bceba2e4" />




### RESULT: 
Thus the code was errorless and runed successfully
