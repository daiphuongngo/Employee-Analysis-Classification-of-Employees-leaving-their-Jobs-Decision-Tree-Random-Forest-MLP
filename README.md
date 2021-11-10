# Employee-Analysis-Classification-of-Employees-leaving-their-Jobs-Decision-Tree-Random-Forest-MLP

## Overview:

## Language, Classification Methods, Tool:

- Python

- Decision Tree

- Random Forest

- Multi Layer Perceptions (MLP) 

- Deep Neural Network

## Classification requirements

- Based on the Train set, predict on the Test set which employees would quit the jobs (field 'Attrition')

- Find out the main reason why they leave their jobs

- Examine an HR policy to retain the employees and specify how it would affect their decisions

## Dataset

- train.csv with size (1000,27)

- test.csv with sizec (470,26) 

## Targets

- Follow with steps of classification using Tree

- Visualize datasets

- Calculate correlations between features

- Process categories

- Build model and compare accuracy of the Decision Tree with other models using other algorithms

- Use model to predict and examnine hypothesis

## Correlation between features using the Pearson correlation

<img src="https://user-images.githubusercontent.com/70437668/141025341-0672dd27-cb79-4efb-a496-ff983e923a43.jpg" width=50% height=50%>

# 4. Build Model

## Decision Tree - Feature Importance

![Decision Tree](https://user-images.githubusercontent.com/70437668/141026829-348613aa-3f9a-4053-b8b4-592032e45d23.jpg)

## Decision Tree - Reasons which might cause employees to quit the jobs or not

![Decision Tree 2](https://user-images.githubusercontent.com/70437668/141026837-45dc2725-a1f2-4d85-8542-19d162f4097c.jpg)

## Random Forest - Feature Importance

![Random Forest](https://user-images.githubusercontent.com/70437668/141026907-abf432f0-df19-4765-811c-d344dcc77a48.jpg)

## Random Forest - Reasons which might cause employees to quit the jobs or not

![Random Forest 2](https://user-images.githubusercontent.com/70437668/141026913-b1420f86-52e2-4375-94ce-c397bf32d1f8.jpg)

## ROC & AUC

![ROC AUC](https://user-images.githubusercontent.com/70437668/141026773-1cd31a10-59b3-4324-b7f5-e98fb1b3535d.jpg)

## **Why is the Random Forest is better than Multi-Layer Perceptron (MLP) in this project while the Neural Netork is a modern and highly valaued algorithm?**

![alt text](https://www.researchgate.net/profile/Benoit_Gallix/publication/324457640/figure/fig1/AS:622298201595905@1525378861825/Graph-illustrating-the-impact-of-data-available-on-performance-of-traditional-machine.png)

Random Forest is less computationally expensive and does not require a GPU to finish training. A random forest can give you a different interpretation of a decision tree but with better performance. Neural Networks will require much more data than an everyday person might have on hand to actually be effective. The neural network will simply decimate the interpretability of your features to the point where it becomes meaningless for the sake of performance.

# 5. Predict employees who will quit the job

![Predict employees who will quit the job](https://user-images.githubusercontent.com/70437668/141026715-2a5dd8a3-d085-4d96-be28-947ba9f1d188.jpg)

# 6. Examine an HR policy

## **Final Result** 

If the company could remove the Over Time policy, employees could stay at the company to work for longer.
