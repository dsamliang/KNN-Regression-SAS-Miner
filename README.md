# KNN-Regression-SAS-Miner

**Dataset:** data.csv (House Price Prediction: https://www.kaggle.com/datasets/shree1992/housedata)

**Steps:**
1. Create Diagram
2. Drag File import node from Sample
3. Select Input Features and Partition Data (40,40,20 for validate, train, and test respetively)
- ![image](https://user-images.githubusercontent.com/98597962/160195410-3e532658-bb5e-4eb8-ae69-2ceed00d02b6.png)
5. Drag MBR node from Model (Memory-based reasoning node is a modeling tool that uses a K-nearest neighbor algorithm to categorize or predict observations)
6. Choose KNN Parameters 
- Method: Scan (Retrieves a nearest neighbor by scanning naively through every observation in the dataset and calculating its distance to a probe observation)
- ![image](https://user-images.githubusercontent.com/98597962/160195466-279e92f6-c210-4abc-a619-de4ec4d68f0b.png)
7. Run and Visualize results

**Results:**

Number of Neighbors: 3
- ![image](https://user-images.githubusercontent.com/98597962/160195973-0121d94f-e30a-496d-9d72-176eab68c93f.png)

Number of Neighbors: 7
- ![image](https://user-images.githubusercontent.com/98597962/160196437-23ef8805-adf0-40bc-ad43-12835a3aeefa.png)
