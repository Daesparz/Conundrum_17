# Fashion Reviews preparation

### Conundrum 17 [Dataiku](https://community.dataiku.com/t5/Community-Conundrums/Conundrum-17-Fashion-Reviews-preparation/td-p/8517)
 
#### Situation
We have obtained a dataset of user reviews for fashion items in our store. Before this information becomes useful for our Machine Learning processes, we need to prepare, clean and shape it into a useful format. In addition, we should also explore what this data contains and perhaps gain some initial insights.

But this is not a one-off exercise, we need to be able to run this pipeline on demand, hence once it is built, a scenario has to be configured to refresh the data, and run metrics and checks where applicable.

There are two paths that could be taken, one purely using the DSS visual elements and another using pure code (Python or R), of course something in between could work too!
 
#### Objective
We need to bring our data into DSS, explore the dataset, clean and prepare for a ML pipeline. 

#### To do list
- Download into a folder and/or dataset
- Clean the data to prepare and normalize the dataset, filter unnecessary data, etc.
- Run some statistics on the clean dataset, such as Univariate and Bivariate analysis and correlation between features.
- Since some of the use cases will involve working with the text of the reviews, create metrics to compute how many reviews have empty title or text.
