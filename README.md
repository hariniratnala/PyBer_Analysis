# PyBer Challenge

## Overview

The purpose of this analysis was to comb through ride sharing data nd determine key metrics that will allow V. Isualize to compare rural, suburban, and urban cities' rides. This included total rides, drivers, and fares, as well as average fares per ride and per driver. This data was organized to various tables.

## Results

create a PyBer summary DataFrame with all the data gathered from Steps 1-5, using the column names shown below:

![image](https://user-images.githubusercontent.com/108489186/181389209-b65bbdcb-7510-46b1-804a-950748f3da63.png)

There are several significant observations to be made while looking at the data when sorted by city type

![image](https://user-images.githubusercontent.com/108489186/181386067-2b6eb6f8-18e7-4fcf-a2bf-d1911e8350b8.png)

 In cells where there is no fare to be summed for that row, the cell will be filled with NaNs.
 
 ![image](https://user-images.githubusercontent.com/108489186/181389380-e4a56332-2ff7-4de0-8744-501f824943f0.png)

After creating the resampled DataFrame, confirm that your DataFrame looks like this:

![image](https://user-images.githubusercontent.com/108489186/181389504-ea8778fd-392a-425c-82a1-9c58bc0dd787.png)

As cities became more urban several trends emerged: -Total rides, total fares, and total drivers all increased, likely due to the higher population -Average fare per ride and average fare per driver all decreased

![image](https://user-images.githubusercontent.com/108489186/181386197-2a10054e-8f0b-4144-8b05-0123d4cf7615.png)

## Summary

The data may be used to consider the following:

1. Such a vast difference in avg fare per driver may pull drivers out to the suburbs/rural areas. Consider researching pay per mile and tweaking the pay structure if the pay per mile is significantly higher in less urban areas

2. Consider increasing the fare in urban areas for more profit since almost 2/3 of rides are in urban areas

3. Consider incentives to hire more suburban/rural drivers since the avg fare is so high. Whether this is to high demand or longer rides or some other factor should be investigated. If rides are more profitable then getting more rural/suburban business should be a top priority
