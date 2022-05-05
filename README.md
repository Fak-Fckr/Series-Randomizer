# Series-Randomizer
Randomly watch your favorite series.

This code just randomly redirects you to series that you can watch randomly. **I do not encourage usage of pirated sites in any way.**

## Adding new series to the list

1. Add the name of the new entry to the list preceded by ```#@param``` in ```line 2```.
2. Add the entry to ```show_dict``` in the following format:
   - ```"Series Name" : (((S1, #Episodes_in_S1), (S2, #Episodes_in_S2), ... (Sn, #Episodes_in_Sn)), link_to_series)```
3. The ```link_to_series``` should include the link with season and episode placeholders removed. For example, if ```"www.watchbojack.com/season_1_episode_3"``` redirects to season 1, episode 3, the the ```link_to_series``` should be provided as ```"www.watchbojack.com/season_{}_episode_{}"```. Note the curly braces ("```{}```") in the url.

That's all, fellas. Just select the show, run the cell, and you would be redicted to a random episode of your favorite show.

I would suggest you save the notebook to your Google Drives as a Colab file so that you may run it from anywhere you want by just sharing the link (sort of like a website at this point).
