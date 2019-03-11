# chronix.benchmark-data
This repository contains the time series of two projects (P4 and P5). These were used to evaluate different time series databases. The evaluation is described in the paper (https://www.usenix.org/system/files/conference/fast17/fast17-lautenschlager.pdf). In contrast to the time series used in the paper, these time series are made anonymous (names of the time series).

## Structure
The file names contain information separated by "\_": `<host>_<process>_<logical-group>_<name>_<date>`
A pair of a time series conists of a timestamp and a numeric value.

Example: `12.08.2015 17:25:40.964;213,385,216` (note that they are `;`-separted)

All files are zipped to reduce space (\*.csv.gz).

## P4
P4 contains 498 time series with 3.8 mio pairs of time stamp and numeric value (data of a few hours measurement)

## P5
P4 contains 24,055 time series with 3.8 billion pairs of time stamp and numeric value (data of up to three months)
