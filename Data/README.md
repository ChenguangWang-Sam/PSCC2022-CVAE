## For "CASE STUDY: EUROPEAN LOAD DATA"
* Historical hourly load data "13-17_32.csv" for 32 European countries between 2013 and 2017 was obtained from the Open Power System Data platform (package version 2019-06-05).
     * Data is available on https://data.open-power-system-data.org/time_series/2019-06-05.
     * Columns of AL, CS, CY, GB, TR, and UA were dropped for incomplete records. 
* Add extra information (i.e., week of year and hour of the day) to historical hourly load data as "13-17_32_conditioned".
* The historical data was randomly split into a training set ("13-17_32_Train.csv") and a test set ("13-17_32_Test.csv") in blocks of one week with the proportion of 4:1 (35,148 training and 8,569 test samples).
* "Train_load_at_2.csv", "Train_load_at_10.csv" and "Train_load_at_21.csv" are load data for 32 European countries between 2013 and 2017 at 2:00, 10:00 and 21:00, respectively.

## For "MULTI-AREA ADEQUACY ASSESSMENT"
* Historical hourly load data "17-18_35.csv" for 35 European countries between 2017 and 2018 was obtained from the Open Power System Data platform (package version 2019-06-05).
     * Data is available on https://data.open-power-system-data.org/time_series/2019-06-05. 
     * Columns for CS, IS, and UA were omitted.
* Add extra information (i.e., week of year and hour of the day) to historical hourly load data as "17-18_35_conditioned".
