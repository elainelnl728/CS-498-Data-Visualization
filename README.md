# Relationship Between Medical Expenses and BMI Across Smokers and Non-Smokers

Please click HERE to visualization page
#Introduction
In this project, I use the dataset on Kaggle that was obtained from the book of Machine Learning with R by Brett Lantz. This dataset contains 1338 data with a total of 7 feature including 4 numerical (Age, BMI, Children, and Expenses) and 3 nominal (Sex, Smoker, and Region) features. No missing or undefined values are found in this dataset.

#Messaging
With this narrative visualization, I am trying to show the relationships between medical expenses and BMI on smokers and non-smokers.

#Narrative Structure
This project’s structure is based on narrative visualization by using interactive slideshows. On the scatterplot page, there are four scenes where the viewer can look at the full data as well as highlighted data based on a categorical variable. Viewers can explore every step of the story following every scene. Also, one more page is added to provide more details about the dataset, the gender, and age of two the two categorical groups: smokers and non-smokers.

#Visual Structure
In the scatterplot page, a stepper model is used for the visual structure, and it displays each scene with descriptions after clicking the “Viz-Scene” button. The mouseover feature is also applied to highlight different categorical data. When viewers click the “Viz-Scene” buttons, the captions on each scene also change to guide the viewer along with the stories. Viewers can easily figure out different categories on each scene based on the colors in the legend of the chart. In the stacked bar chart plot, the tooltip is used to provide detailed information of each section of the bar to provide some other aspects of the dataset.

#Scene
There are five scenes in the narrative visualization: four scenes in the scatterplot and one additional scene in the stacked bar chart plot. The same template and layout are designed for the visual consistency.

#For the scatterplot:

The first 4 scenes were designed in the same template and style for visual consistency, which will not make user disoriented when changing scenes.
The scatterplot automatically shows the first scene and allows viewers to move mouse to highlight the categorial data for smokers and non-smokers. Viewers will get a broad view of the data trend in scene 1.
To view scene 2, viewers need to click the “Viz-Scene 2” button, which located next to “Viz-Scene 1” button. After clicking the button, scene 2 shows “Smokers tends to have higher medical expenses than non-smokers.” and implicitly guide the viewer to locate smokers and non-smokers data.
For Scene 3, the button is located next to “Viz-Scene 2”, and it guides the viewer to explore the data with BMI>30 based on the categorical variable "smoker" or “non-smoker”. It reveals a positive correlation between the medical expenses and BMI when people are smokers.
For Scene 4, which is the last scene in the scatterplot, it indicates smoking can magnifies the bad effects of obesity on people's health and ask the viewer to reflect on this trend and consider not to smoke for personal’s health.
At the bottom of each scene page, it will direct the viewer to the next page which is the stacked bar chart page (scene 5).
For the stacked bar chart page:

In Scene 5, there are two stacked bar graphs in the same template. The left bar graph summarizes the gender of the smokers and non-smokers. The dataset contains two types of gender: female and male. The right bar graph summarizes the ages, which is separated into 6 groups from 18 to 64 years old.
At the bottom of the right paragraph, it will direct the viewer to return to the homepage or the scatterplot page.
Annotations
The annotations are used in the scatterplot to highlight a trend in the data. Within the scatterplot, the annotations are designed in a consistent template with same font size and bolded style. These annotations direct the user to further investigate the data and ask the user to draw a conclusion from the data.

The annotation in Viz-Scene 1 is meant to imply the viewers about the functions of user engagement with the data. Viewers are invited to mouseover the data to see the trends for smokers and non-smokers independently.
The annotation in Viz-Scene 2 is meant to highlight the primary finding of the visualization.
The annotation in Viz-Scene 3 is meant to ask the viewer to think about the important role of smoking when the BMI is over 30. Viewers can be directed to see the positive correlation of medical expenses and BMI when BMI is over 30.
The annotation in Viz-Scene 4 is to ask viewers to reflect on what has been discovered in this narrative visualization and to seriously consider not to smoke for personal’s health conditions.
For all the annotations in these scenes, when viewers click the button to transit to a different scene, the annotations of the last scene will disappear and instead display the next annotations for that scene.

#Parameters
The parameter used in this visualization is the categorical variable "Type" and viewers can explore one type of data at a time by moving the cursor on the data that is smoker or non-smoker.

When mousing over the data belonging to a particular type, the current state will change to that specific type. This allows the user to gain more information about the relationship between medical expenses and BMI, not only as overall trend, but also based on the smoking type as well. On the second page, I also used the mouseover functions to indicate the gender and age information based on specific types of smoking groups.

#Triggers
Triggers are used in two ways for this visualization.

First, the buttons on top of the visualization in each scene are triggers to change scenes. It contains the affordance to guide the viewer with available actions. The buttons are labelled to "Viz-Scene 1", "Viz-Scene 2", "Viz-Scene 3", and "Viz-Scene 4”, which make the functions obvious to viewers. Upon clicking each scene button, the current state of the visualization will trigger a change to a different state and shows different annotations. Also, when user mouse over the scene buttons, the button will be temporarily highlighted with brightness. That provides affordance to viewers since they will notice that and understand that this button can be clicked.

Second, a trigger is also set within the data. When viewers mouseover to each data, the current state of visualization will trigger a change to that specific type of data that is currently moused over. That will show a colored highlight for that specific type of people either smokers or non-smokers. The "mouse leave" function also changes the current state of the chart and do not highlight the data when mouse leaves that type of data points. The triggers are applied in every scene from scene 1 to scene 5.

#References
Dataset Source: Medical Cost Personal Datasets on Kaggle
Scatterplot, stacked bar plot, tooltip exmaples: D3 graph gallery
Stepper model template: Dynamic Annotations in a Visualization Stepper