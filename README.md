# Reaf_life_data_project

On this repository you will find the following notebooks: 

**DATA LOAD**
* Code that loads all data from season 3. This file will collect functions from following notebooks: 
> * Angle
>> * calculate angle between two vectors

> * DELTA 
>> * Calculate time between the boat round the mark and the first boat rounding a mark 
> * Leaderboard 
>> * Calculating the position that a boat rounds a mark
> * sequence 
>> * Calculate the perioed of a race to exclude all non-racing data
> * race_timestamps 
>> * is used to for the function 'sequence'

**TWD_gate_angles**
* This notebook is the primary notebook. It has the following Table of Contents:
> * **0. Introduction**
    >> * 0.1 Problem definition
* > * **1. Loading and preparing XML files (race course)**
> * **2. Meters won at gate marks**
    >> * 2.1 Meeters gain by taking left turn at LW gate (LW1 gate mark)
>> * 2.2 Meeters gain by taking left turn at top gate (WW gate) 
>> * 2.3 Subconclusion
> * **3 Detecting TWD**
>> * 3.1 TWD vs TWD_TM_deg
>> * 3.2 Calculating True TWD
>>> * 3.2.1 One boat at a time
>> * 3.3 Create a column with median_TWD_leg
>>> * 3.3.1 Now merging the df_median_TWD and df_merged
> * **4 Defining what mark the boat takes**
>> * 4.1 Subconclusion
> * **5 Dividing the gate in LW_gate and WW_gate and calc boats won**
>> * 5.2 Subconclusion 
> * **6 How much bias is needed?**
>> * 6.1SubConclusion
> * **7 ANOVA test**
> * **8 Splitting with the fleet**
>> * 8.1 Subcnclussion 

**XML positions and maps**
* This notebook contain the load of XML files and plotting of the courses around the world. 



