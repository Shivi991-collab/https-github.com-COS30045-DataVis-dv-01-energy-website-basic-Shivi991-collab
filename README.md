## Week 3 Exercise 

Issue to talk about this week is the impact of the screen size on the energy consuption.

### About the data:

**Data Source**: the data is sourced from the csv file provided in week1. I used KNIME to extract the data from the file and analysed it.

**Data Processing**: The KNIME platform uses a node called CSV reader to extract the data to the platform where i could actually work with it and manipulate it accordingly. I used several other nodes such as column filter to filter out the columns that were needed, expression node to convert the screen size from cm to inches and also to divide them into the large, medium and small category according to their screen size, groupby noded to group the tv size with the mean of their energy consumption and finally the bar chast node tol depict the whole data visually.

**Privacy**: The data used is publicly accessible.

**Accuracy and Limitations**: The accuracy depends on the dataset used, so having a clean and concise data with no flaws is the key to get better result. The bar chart for one of the instances did not match exactly as depicted in the canvas was due to different datasets being used to calculate and visualize the dataset.
The only limitation faced was the tv screen size being in cm so it needed to be converted to inches for better understanding of the data which was achieved through the expression node.

**Ethics**: All information is accurately depicted in the visualizations.



 
