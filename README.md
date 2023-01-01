# Leap Motion Essay Raw Data

The following repository contains the rawa data for the Essay named "What Data-Driven Approach Can Teach Us About Interpersonal Synchronization?".<br><br>


The data included consists of 2two distinct parts: the raw data before and after preprocessing.<br>
The preprocessing manipulations on the data were as follows:<br>
* The data for every participant was united into a single dataframe, while adding labels to maintain separation of experiments
* The first seven seconds of every recording were removed to maintain experiment pureness
* The data which was not correctly captured by the Leap Motion device (i.e. only 1 hand of the two was captured etc.) was removed
* Unitingg the right and left hand records (two consecutive rows into a single row in the dataframe)
