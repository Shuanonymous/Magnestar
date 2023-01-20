My solution to the coding exercise for Magnestar
Given a supplied data file containing gathered satellite information and telemetry for 333 active space satellites, we ask that you produce a script that:
    Reads in the satellite data CSV file
    Optionally filters the data by either Operator and/or Frequency Band
    Output subset of columns for the filtered results

exercise.jpynb will prompt a user for a filter, specifying inputs such as OP for operator, or F for Frequency Band. Once the user inputs the filter, the data is filtered to the requested filter, and all null values are removed. The data is displayed to the user with a display message indicating the filter used. 