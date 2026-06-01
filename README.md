## Cleaning and Extracting Causes ##
This notebook contains code that was used to clean the original dataset.
Note that I also did some manual cleaning after.
To extract the causes from the summaries, I first used a word mapping to assign each crash a category and train a supervised learning model.
Then, I used the model to predict labels for some of the "Other/Unknown" crashes.
The word mapping and model in this code isn't the same one I used for the Tableau visualization, as I have been refining them, but the general process is pretty much the same.

## Aircraft Crashes With Causes Dataset ##
This is the dataset used for the Tableau visualizations, which has causes that were labeled using the original word mapping and model.

## Tableau Workbook ##
This packaged workbook contains the visualizations used in the Medium post.
