# Assignment 1

## Part A - Characterise the series (time domain)


The Meridional Overturning Variability Experiment (MOVE) is a moored array in the western Atlantic along 16°N, measuring North Atlantic Deep Water (NADW) at depths of 1200 to 5000 meters. NADW is the deep, southward flowing part of the AMOC, balancing warmer flows at the surface, such as the Gult Stream.

The dataset contains 4164 observations at a sampling interval of 48 hours from 2000-02-06 until 2022-10-14, with a low-pass filter of 10 days. 180 out of those data points are missing values.

The timeseries including monthly averages can be seen here:
![MOVE 16°N timeseries of NADW.](plots/timeseries.png)

Since the entire timeseries shows negative transport values, the measurements confirm that NADW flows southward, with an average transport of -16.9 Sv and standard deviation of 4.5 Sv.
The transport varies between -3.3 and -31.9 Sv, covering a range of 28.5 Sv.

The distribution of MOC transport is shown here: 
![MOVE 16°N NADW transport distribution.](plots/hist.png)

## Part B - The spectrum (frequency domain)