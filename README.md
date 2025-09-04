# Landslide-machine-learning
This is a basic UNET model implementation that i copied from https://www.youtube.com/watch?v=IHq1t7NxS8k&ab_channel=AladdinPersson . 
I changed the channel size input to fit the 14 different vectors for each set of data

Improvements:
The actual test dataset is not available from the data, as it was used in a competition of some sorts.
To better show accurate masks, i should have split the available training data into something like an 80/20 split.
Train on the 80% then test on the remaining 20 rather than testing on already used training data.
I only tested a few just to see if it actually output some accurate masks and it did.

A better improvement would be to be able to generate some insights about what parts of the data contribute most to 
landslide risk.
