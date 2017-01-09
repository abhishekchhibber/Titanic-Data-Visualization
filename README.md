# Titanic Data Visualization
_Visualization of Titanic Dataset_

## Summary
In this project, I have tried to analyze the Titanic dataset, based on the following categorical features:
* Survived: 1 = Yes, 0= No
* Pclass (Passenger Class): 1,2,3
* Sex: Male, Female
* Embarked (Port of Embarkation): C = Cherbourg, Q = Queenstown, S = Southampton

I have tried to understand the relationship among all the four categorical features. [Link to the dataset](https://www.udacity.com/api/nodes/5420148578/supplemental_media/titanic-datacsv/download) 



## Design

I followed the following process to analyze the data and present it:


#### Step 1: Analyzing Data
I used Python (pandas) to analyze the data in an [IPYNB notebook](https://github.com/abhishekchhibber/Titanic-Data-Visualization/blob/master/titanic%20data%20analysis.ipynb). Taking the four categorical features, 

Taking the four categorical features, I created six different charts using two features. Thereafter, I used Pandas and Numpy to create pivot tables and saved them as separate .tsv files. I hosted these .tsv files on Google Drive and used the link to call the data.

#### Step 2: Creating Initial Charts and receiving feedback
Using the data generated in IPYNB notebook, and save as .tsv on Google Drive, I created a HTML file with six charts, and shared it with my acquaintances.

The initial visualization is saved as [index_first.html](https://github.com/abhishekchhibber/Titanic-Data-Visualization/blob/master/Index_first.html)

#### Step 3: Sketching the final visualization
Based on the feedback, I tried to create the final visualization, which can depict relationship between all four categorical features, using only a single chart. I initially started with creating a bubble chart of pie charts - where two features will come on two axis, third feature as size of bubble, and fourth features as the pies. However, the chart became more confusing, and did not work as per the feedback. 

Finally, I used Dimple.js to create simple pie charts. The library helped me to get all the four features onto a single visualization – which the end user can easily see using hover tip. I further added a svg element to label the legend, and also created a table for keys to understanding the data. 

The final visualization is saved as [index_final.html](https://github.com/abhishekchhibber/Titanic-Data-Visualization/blob/master/Index_final.html)

## Feedback

I shared the index_first.html with three of my acquaintances, and received their feedback. Following is the summary of feedbacks:

**Feedback 1:**
_"The charts are a bit confusing. They do not tell what exactly do you want to show, and what should I infer from them. Also, there is no legend, or explanation."_ 


**Feedback 2:**
_"It’s a bit blunt. Add something to tell the reader/viewer what they should be looking at. Also, can you condense them to less number of charts?"_

**Feedback 3:**
_"There is a lot of ambiguity. Can you write something for the reader to understand? Use different charts or colors, or club some of the charts together to make it more meaningful."_ 

## Further Exploration
I wanted to explore the data using a Chord Diagram. Therefore, I used d3.js and viz.js to create another visualization using a chord diagram. I used Python code to create a list of lists with all the different combinations of features as well as their sub features. Thereafter, I used an existing template of chord diagram and used it to create my visualization. 

The visualization is saved as [index_chord.html](https://github.com/abhishekchhibber/Titanic-Data-Visualization/blob/master/Index_chord.html)



## Resources
* https://www.kaggle.com/c/titanic
* D3.js
* Dimple.js
* Viz.js


