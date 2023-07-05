# Advanced_deep_learning_project
this is the visualization part for the advanced deep learning project by Shay Matok and Ron Garshowitz

In the EDA phase we created these visualizations, Here we will present only few examples, all of the rest exist in the repository).

1. At first we looked at the labels distributions, not including null values (not all pr:
  
![main category](https://github.com/Rgarshowitz/Advanced_deep_learning_project/assets/95139813/d660ab15-e453-4af9-80ee-c779de448572)

![1st sub category](https://github.com/Rgarshowitz/Advanced_deep_learning_project/assets/95139813/a84b5a7b-8626-4c8b-9e97-062444fc4e1c)

The conclusion is that the dataset isn't balanced and we mentioned it further in the report.

2. We wanted to check if there is a relation between the publish date and the categories of the articles:

![Article count by categories over time](https://github.com/Rgarshowitz/Advanced_deep_learning_project/assets/95139813/6d484c35-ec00-47b3-b046-ae602211704e)

The connection exists of course and we used it to our model's advantage.

3. The most common words in the data and in every category:

![WordCloud - most common words in data](https://github.com/Rgarshowitz/Advanced_deep_learning_project/assets/95139813/e371bc07-0f3a-420e-8ef1-eebbe0722148)

![WordCloud - most common words in Lifestyle Category](https://github.com/Rgarshowitz/Advanced_deep_learning_project/assets/95139813/ebfdd937-36b9-48c4-a345-27857d202606)

![WordCloud - most common words in Sport Category](https://github.com/Rgarshowitz/Advanced_deep_learning_project/assets/95139813/b41ffb60-01fe-4b2d-a3d3-02e323f303c4)

4. (Please don't skip this part!)
In the last visualiztion part and the major one we used Scattertext to analyze TF-IDF scores of each category compared to all the rest. the results show a variety of words which are related to one category much more compared to the others in a visual and interactive way. Those representations are the html files in the repository and they take approximatly 1 Min of loading on the browser (You just need to press wait for loading).

Thank you!
