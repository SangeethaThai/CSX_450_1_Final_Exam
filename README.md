# CSX_450_1_Final_Exam


## Description of the Abalone dataset


  The Problem is to predict the age of the Abalone from Physical Measurements.
  
  Normally, an Abalone's age is normally predicted by cutting the shell and counting the rings inside. So to automate this repetitive, boring, manual task physical measurements of the Abalone are collected to predict its age.

The last column "Rings" is the Target or the variable we want to predict.



### Size of the Dataset

  a) The dataset contains 4177 rows and 9 columns (8 features + 1 target).
  
  b) Size of data on file system is 191873 bytes
  
  c) Size of data when loaded in memory is 269528 bytes



### Data Types

   While the data type of attribute "Sex" is Character (which may fall into categories "F", "M", "I" (Infant)), other attributes are of type numeric (float).

   Target variable, Ring's datatype is integer.
   
       Name		Data Type	Meas.	Description
        ----		---------	-----	-----------
        Sex		nominal			M, F, and I (infant)
        Length		continuous	mm	Longest shell measurement
        Diameter	continuous	mm	perpendicular to length
        Height		continuous	mm	with meat in shell
        Whole weight	continuous	grams	whole abalone
        Shucked weight	continuous	grams	weight of meat
        Viscera weight	continuous	grams	gut weight (after bleeding)
        Shell weight	continuous	grams	after being dried
        Rings		integer			+1.5 gives the age in years
    
    The number of Rings can be predicted using either a Regression Algorithm or Classification Algorithm
    
    Classification distribution data related to this is:
    
        Class	Examples
        -----	--------
        1	1
        2	1
        3	15
        4	57
        5	115
        6	259
        7	391
        8	568
        9	689
        10	634
        11	487
        12	267
        13	203
        14	126
        15	103
        16	67
        17	58
        18	42
        19	32
        20	26
        21	14
        22	6
        23	9
        24	2
        25	1
        26	1
        27	2
        29	1
        -----	----
        Total	4177
    
    
    
### Features and Target

   The features or independent variables or the predictors are Sex, Length, Diameter, Height, Whole Weight, Sucked Weight, Viscera Weight and Shell Weight.

   The target or the dependent variable or the variable we want to predict is Rings
   
   
### Summary Statistics
  
   Summaries for all attributes give us a little more insight into the data contained in dataset. 
   
   ```
  Sex          Length         Diameter          Height        Whole weight   
 F:1307   Min.   :0.075   Min.   :0.0550   Min.   :0.0000   Min.   :0.0020  
 I:1342   1st Qu.:0.450   1st Qu.:0.3500   1st Qu.:0.1150   1st Qu.:0.4415  
 M:1528   Median :0.545   Median :0.4250   Median :0.1400   Median :0.7995  
          Mean   :0.524   Mean   :0.4079   Mean   :0.1395   Mean   :0.8287  
          3rd Qu.:0.615   3rd Qu.:0.4800   3rd Qu.:0.1650   3rd Qu.:1.1530  
          Max.   :0.815   Max.   :0.6500   Max.   :1.1300   Max.   :2.8255  
 Shucked weight   Viscera weight    Shell weight        Rings       
 Min.   :0.0010   Min.   :0.0005   Min.   :0.0015   Min.   : 1.000  
 1st Qu.:0.1860   1st Qu.:0.0935   1st Qu.:0.1300   1st Qu.: 8.000  
 Median :0.3360   Median :0.1710   Median :0.2340   Median : 9.000  
 Mean   :0.3594   Mean   :0.1806   Mean   :0.2388   Mean   : 9.934  
 3rd Qu.:0.5020   3rd Qu.:0.2530   3rd Qu.:0.3290   3rd Qu.:11.000  
 Max.   :1.4880   Max.   :0.7600   Max.   :1.0050   Max.   :29.000  
   ```
   

### Distributions

   Plotting a Histogram of the Target Rings, it seems like most Abalone in the dataset have Rings between 6-13 (age 7.5 - 14.5) approximately,.

  Running a regression plot on the data displays the regression relationship between the target and features as well as between the features. Some Linear and some not so Linear, although all relationships seem to be positive (trending upward).


   
## Author
   
   **  Sangeetha Parthasarathy  **