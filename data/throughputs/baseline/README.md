## Baseline throughput curves.  ##

The throughput curves in this directory should be considered
'baseline' for the current behavior of LSST. These curves are
identical to those considered in the SRD except that only y4 (as 'y')
has been included here (for simplificiation) and an X=1.2 atmosphere
has been used to compile the 'total' throughputs.

Note that these throughput curves are subject to change as our knowledge
of the LSST systems improve and prototypes become available.


m1.dat, m2.dat, m3.dat represent the current mirror throughputs used in the SRD.
lens1.dat, lens2.dat, lens3.dat represent the current lens throughputs ""
detector.dat is the current detector sensitivity in the SRD.

filter_u / g / r / i / z / y. dat represent the current filter (filter only!)
  throughput curves used in the SRD. Note that y = y4 is the current baseline filter.


atmos_std.dat is the atmosphere throughput likely at LSST at 1.2 airmasses.

total_*.dat throughput curves represent the combination of all components in the LSST
  system - mirrors, lenses, filter, detector, and the zenith atmos_std.dat atmosphere.

All curves are in nanometers, with throughput represented by a number between 0 and 1.


### Information about the source of these files is available in README_SOURCE.md ###
