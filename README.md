# Data Analysis Projects
Portfolio of some personal data analysis projects. More on the way!
1. [Persistent Homology of Stack Overflow Tags](Persistent-Homology-of-Stack-Overflow-Tags)
2. [Visualizing Stack Overflow Tags](Visualizing-Stack-Overflow-Tags)
3. [Recommendation System for Stack Overflow Users](Recommendation-System-for-Stack-Overflow-Users)
## Persistent Homology of Stack Overflow Tags
In my first project, I tried to [compute the persistent homology of the most popular Stack Overflow tags](https://github.com/daniel-rossano/Data-Analysis-Projects/blob/main/Persistent%20Homology%20SO%20Tags/Persistent%20Homology%20of%20Stack%20Overflow%20Tags.ipynb) to understand how they are linked together. Although it is not perfect, it was done to learn some techniques on working with large data sets in pandas. The project is saved as a Jupyter Notebook, and all relevant data has been made available along with the barcode and persistence diagram. <img src="https://user-images.githubusercontent.com/123789570/246283541-32f5d9b1-0af4-4342-88a5-74494eede5e1.png" width="50%" height="50%"/>

## Visualizing Stack Overflow Tags
As a follow-up to the first project, I [used KeplerMapper to visualize clusters of Stack Overflow tags](https://nbviewer.org/github/daniel-rossano/Data-Analysis-Projects/blob/main/Visualizing%20Stack%20Overflow%20Tags/Visualizing%20Stack%20Overflow%20Tags%20Using%20KeplerMapper.ipynb). A significantly different approach than the previous project, I used dimensionality-reduction techniques and clustering algorithms to best fit and preserve the data assigned to the Stack Overflow tags. After applying some new techniques I learned in Python, I was also able to make significant run-time improvements in the pre-processing stage!

<img src = "https://user-images.githubusercontent.com/123789570/246283683-b425d5a1-0849-4253-aa75-ba912ab14824.png" width="50%" height="50%" />

## Recommendation System for Stack Overflow Users
A summation of the knowledge I gained from the previous two projects, I [built a content-based recommendation system for Stack Overflow users](https://github.com/daniel-rossano/Data-Analysis-Projects/blob/main/Recommendation%20System%20for%20Stack%20Overflow%20Users/Recommendation%20System%20for%20Stack%20Overflow%20Users.ipynb) to recommend questions to users who have posted at least one question to the site. Two different techniques are used to assess and recommend the most relevant questions to users before scaling the project to recommend questions catered to a user based off of all the questions they have asked!

<img src="https://github.com/daniel-rossano/Data-Analysis-Projects/blob/main/Recommendation%20System%20for%20Stack%20Overflow%20Users/Samples/RecommenderScreenshot.png?raw=true" width="70%" height="50%"/>
