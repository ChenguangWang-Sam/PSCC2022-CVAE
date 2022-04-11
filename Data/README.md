 ## For "CASE STUDY: EUROPEAN LOAD DATA"
 * Historical hourly load data "13-17_32.csv" for 32 European countries between 2013 and 2017 was obtained from the Open Power System Data platform (package version 2019-06-05).
     * Data is available on https://data.open-power-system-data.org/time_series/2019-06-05.
     * Columns of AL, CS, CY, GB, TR and UA were dropped for incomplete records. 
 * The historical data was randomly split into training set ("13-17_32_Train.csv") and test set ("13-17_32_Test.csv") in blocks of one week with the proportion of 4:1 (35,148 training and 8,569 test samples).
 

 ## For "MULTI-AREA ADEQUACY ASSESSMENT"
  * Historical hourly load data "17-18_35.csv" for 35 European countries between 2017 and 2018 was obtained from the Open Power System Data platform (package version 2019-06-05).
     * Data is available on https://data.open-power-system-data.org/time_series/2019-06-05. 
     * Columns for CS, IS and UA were omitted.
