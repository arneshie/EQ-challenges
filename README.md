# EQ-challenges

For this challenge, the Data Science track was attempted. The instructions followed for this project are outlined below:

## Common Problems

### 1. Cleanup

Find the sample dataset of request logs in `data/DataSample.csv`. We consider records with identical `geoinfo` and `timest` as suspicious. Please clean up the sample dataset by filtering out those questionable request records.

### 2. Label

Assign each *request* (from `data/DataSample.csv`) to the closest (i.e., minimum distance) *POI* (from `data/POIList.csv`).

Note: a *POI* is a geographical Point of Interest.

### Choose a track

Depending on the job/role you are applying for, you may be asked to choose one of the following tracks for problems 3 and 4.

## Data Science Track

### 3. Analysis

1. For each *POI*, calculate the average and standard deviation of the distance between the *POI* to each of its assigned *requests*.
2. At each *POI*, draw a circle (with the center at the POI) that includes all of its assigned *requests*. Calculate the radius and density (requests/area) for each *POI*.

### 4. Modelling

1. To visualize the popularity of each *POI*, map them to a scale that ranges from -10 to 10. Please provide a mathematical model to implement this, considering extreme cases and outliers. Aim to be more sensitive around the average and give as much visual differentiability as possible.
2. **Bonus**: Try to develop reasonable hypotheses regarding *POIs*, state all assumptions, testing steps, and conclusions. Include this as a text file (with the name `bonus`) in your final submission.

### Notes

Keep in mind that both the amount and the dimension of the data we work with are much higher, in reality, so try to demonstrate that your solutions can handle beyond the sample scale.
