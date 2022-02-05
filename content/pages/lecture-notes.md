---
content_type: page
title: Lecture Notes
uid: 7db57be8-2ce7-e0cd-b529-3f5578c683b0
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LEC #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
NOTES, SUPPORTING FILES AND LINKS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Overview of the aims of the class ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec1))
{{< tdclose >}}
{{< tdopen >}}


Class introduction and content

[U.S. Coast Guard Navigation Center Website](http://www.navcen.uscg.gov/)  
[University NAVSTAR Consortium Website](http://www.unavco.org/)  
[SCIGN Data Portal Website](http://reason.scign.org/)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
Coordinate and time systems ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec2))
{{< tdclose >}}
{{< tdopen >}}
Introduction to coordinate system definition and realization concentrating on geometric definitions  
[SCO Web: Control Networks](https://www.sco.wisc.edu/surveying/geodetic-standards-networks/)  
[National Geodetic Survey](http://www.ngs.noaa.gov/)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Potential fields and coordinate systems ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec3))
{{< tdclose >}}
{{< tdopen >}}
Potential fields and coordinate systems. We also used some Matlab scripts in this lecture. The two programs are Harmonics.m ([M]({{< baseurl >}}/resources/harmonics)), which plots low order harmonics and Sectorials.m ([M]({{< baseurl >}}/resources/sectorials)), which plots high order sectorial harmonics. Surface harmonic figure and code: SurfaceHarmonic.fig ([FIG]({{< baseurl >}}/resources/surfaceharmonic-1)) and SurfaceHarmonic.m ([M]({{< baseurl >}}/resources/surfaceharmonic))  
[Legendre Polynomial](http://mathworld.wolfram.com/LegendrePolynomial.html)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Coordinate types ([PDF - 1.7MB]({{< baseurl >}}/resources/mit12_540s12_lec4))
{{< tdclose >}}
{{< tdopen >}}
Coordinate systems, rotation of the Earth, Geoid, Spherical trigonometry  
[International Earth Rotation and Reference Systems Service](http://www.iers.org/)  
Modeling of Nutation-Precession: Very long baseline interferometry results (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF](http://geoweb.mit.edu/~tah/12.540/icd200cw1234.pdf))  
[Computation of Geoid99 Geoid Height](http://www.ngs.noaa.gov/cgi-bin/GEOID_STUFF/geoid99_prompt1.prl)  
[Spherical Trigonometry](http://mathworld.wolfram.com/SphericalTrigonometry.html)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
GPS satellite orbits ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec5))
{{< tdclose >}}
{{< tdopen >}}
GPS satellite orbits. The MATLAB program to compute eccentic and true anomalies is truea.m ([M]({{< baseurl >}}/resources/truea))  
The GPS interface control document (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF](http://geoweb.mit.edu/~tah/12.540/icd200cw1234.pdf))  
Unclassified (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF - 1.3MB](http://geoweb.mit.edu/~tah/12.540/icd200cw1234.Nav.pdf))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
GPS observables ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec6))
{{< tdclose >}}
{{< tdopen >}}
Start analysis of GPS observables in form of carrier phase
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
Specifics of GPS signal ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec7))
{{< tdclose >}}
{{< tdopen >}}
GPS codes on signals
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Pseudorange measurements ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec8))
{{< tdclose >}}
{{< tdopen >}}
Pseudorange and phase measurements. The data file displayed in class is etab.plt.dat ([DAT]({{< baseurl >}}/resources/etab-plt))  
[TEQC—The Toolkit for GPS/GLONASS/Galileo/SBAS Data](http://www.unavco.org/facility/software/teqc/teqc.html)  
RINEX: The Receiver Independent Exchange Format Version 2 ([TXT](./resolveuid/7011abfcc38880524b44d32e07d31bc8))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
Range and phase data ([PDF - 1.3MB]({{< baseurl >}}/resources/mit12_540s12_lec9))
{{< tdclose >}}
{{< tdopen >}}
The data files displayed in class are ASCII tab delimited files: etab.02tab ([TXT]({{< baseurl >}}/resources/etab)) etab.07tab ([TXT]({{< baseurl >}}/resources/etab-1)) etab.11tab ([TXT]({{< baseurl >}}/resources/etab-2)) etab.26tab ([TXT]({{< baseurl >}}/resources/etab-3)) etab.28tab ([TXT]({{< baseurl >}}/resources/etab-4))  
The following files are based on 2008 homework: data from base station with approximate XYZ coordinates  
\-2197259.2644 -4811601.7696 3552341.4441 (m)  
Each file has a header line with column titles. All range and phase units are meters except as noted where range differences have been converted to L1 cycles  
base.02 ([TXT]({{< baseurl >}}/resources/base-6)) base.04 ([TXT]({{< baseurl >}}/resources/base)) base.05 ([TXT]({{< baseurl >}}/resources/base-1)) base.09 ([TXT]({{< baseurl >}}/resources/base-2)) base.12 ([TXT]({{< baseurl >}}/resources/base-7)) base.17 ([TXT]({{< baseurl >}}/resources/base-3)) base.28 ([TXT]({{< baseurl >}}/resources/base-4)) base.29 ([TXT]({{< baseurl >}}/resources/base-5))  
The site coordinates are in the rinex header shown in Lec #8  
Sources of GPS data (main archives)  
[SOPAC](http://sopac.ucsd.edu/)  
[CDDIS](http://cddis.gsfc.nasa.gov/)  
[NGS/CORS](http://www.ngs.noaa.gov/CORS/)  
[UNAVCO](http://www.unavco.org/data/data.html)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
Estimation: introduction ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec10))
{{< tdclose >}}
{{< tdopen >}}
Start estimation looking a parametric estimation methods  
[Data Analysis for Process Modeling](http://www.itl.nist.gov/div898/handbook/pmd/section4/pmd4.htm)  
[Least Squares Parameter Estimation (Regression Analysis)](http://reliawiki.org/index.php/Least_Squares)

histograms.m ([M]({{< baseurl >}}/resources/histograms)) generates histogram plots


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
Statistical approach to estimation ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec11))
{{< tdclose >}}
{{< tdopen >}}
Continue estimation now examining it from a statistical point of view
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Estimation: correlations ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec12))
{{< tdclose >}}
{{< tdopen >}}
Statistical description of process noise in parameter values. The MATLAB program fogm.m ([M]({{< baseurl >}}/resources/fogm)) generates first-order Gauss Markov processes. (Note since the random number generator is not initialized, your results will differ from those in the class notes (Signal processing tool box is needed for the PSD calculation). FlickerNoise.m ([M]({{< baseurl >}}/resources/flickernoise)) implements flckernoise model through PSD->Covarinace Matrix->eigenvectors and values
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
Estimation ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec13))
{{< tdclose >}}
{{< tdopen >}}
Kalman filter approach to estimation
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
Propagation medium: propagation ([PDF - 2.3MB]({{< baseurl >}}/resources/mit12_540s12_lec14))
{{< tdclose >}}
{{< tdopen >}}
Timing in GPS. Examine clock estimation  
[IGS Clock Products Working Group](https://www.nrl.navy.mil/ssdd/research-activities/8150/igs)  
[IGS Time Scale](https://www.researchgate.net/publication/3918247_Developing_an_IGS_time_scale)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Propagation medium: neutral atmosphere ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec15))
{{< tdclose >}}
{{< tdopen >}}
Tropospheric delay estimation  
[The Height of the Tropopause](http://www-das.uwyo.edu/~geerts/cwx/notes/chap01/tropo.html)  
Effects of the Troposheric Mapping Function on Space Geodetic Data (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF - 1.0MB](http://gauss.gge.unb.ca/papers.pdf/igs97tropo.pdf))  
[Index of /DELAY](http://ggosatm.hg.tuwien.ac.at/DELAY/)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Propagation: ionospheric delay ([PDF - 1MB]({{< baseurl >}}/resources/mit12_540s12_lec16))
{{< tdclose >}}
{{< tdopen >}}
Ionospheric delays  
[National Geophysical Data Center](http://www.ngdc.noaa.gov/stp/SOLAR/ftpcalcium.html)  
Data file (Year Month Day SunSpot number)  
[RIDAILY (1811-2012/04)](http://geoweb.mit.edu/~tah/12.540/RIDAILY_120407.txt)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
Basic antenna operation ([PDF - 1.7MB]({{< baseurl >}}/resources/mit12_540s12_lec17))
{{< tdclose >}}
{{< tdopen >}}
Antennas and calibrations  
[NGS/Antenna Calibrations](http://www.ngs.noaa.gov:80/ANTCAL/)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
Mathematical models in GPS ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec18))
{{< tdclose >}}
{{< tdopen >}}
Class starts development of mathematical models needed for precise GPS positioning. In this class we look at solid-Earth tides, ocean-tidal loading and other types of loading effects. The following Fortran source code was discussed in the lecture earth\_tide.f ([F]({{< baseurl >}}/resources/earth_tide)) and gst\_jd.f ([F]({{< baseurl >}}/resources/gst_jd))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
GPS models and processing ([PDF - 1.4MB]({{< baseurl >}}/resources/mit12_540s12_lec19))
{{< tdclose >}}
{{< tdopen >}}
Models: Rank deficiencies, ambiguity resolution and differencing methods
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Processing software ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec20))
{{< tdclose >}}
{{< tdopen >}}
Processing software:  
[GAMIT/GLOBK Web Tutorial](http://geoweb.mit.edu/~simon/gtgk/tutorial/Index.html)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
GPS groups/IGS ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec21))
{{< tdclose >}}
{{< tdopen >}}


GPS data availability and site locations  
[UNAVCO](http://www.unavco.org/data/data.html)  
[International GNSS Service](http://gpsworld.com/tag/international-gnss-service/)  
International GNSS Service—All world map ([PNG]({{< baseurl >}}/resources/all_world))

Networks  
[SCIGN](http://www.scign.org/)  
[UNAVCO](http://www.unavco.org/data/data.html)  
[NGS/CORS](http://www.ngs.noaa.gov/CORS/)  
[Bay Area Regional Deformation Network](https://seismo.berkeley.edu/bard/)  
[Pacific Northwest Geodetic Array](http://www.panga.cwu.edu/)

Results  
[Permanent GPS Site Arrays](http://sopac.ucsd.edu/)  
[GPS Time Series](http://sideshow.jpl.nasa.gov/mbh/series.html)  
[SCIGN Data Portal](http://reason.scign.org)  
[GPS Explorer](http://geoapp03.ucsd.edu/gridsphere/gridsphere)  
[UNAVCO](http://www.unavco.org/data/data.html)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
Kinematic GPS ([PDF]({{< baseurl >}}/resources/mit12_540s12_lec22))
{{< tdclose >}}
{{< tdopen >}}
Kinematic GPS processing and results from experiment earlier in semester  
Results from MIT survey  
track\_LC.out ([TXT]({{< baseurl >}}/resources/track_lc))  
track.NEU.rovr.LC ([TXT]({{< baseurl >}}/resources/track-neu-rovr))  
track.NEU.rovr.L1+L2 ([TXT](./resolveuid/adb820ca15496d7ae116d84a824ae963))  

**Results from the 2010 MIT survey**

TR02.sum ([TXT]({{< baseurl >}}/resources/tr02)) TR02.out ([TXT]({{< baseurl >}}/resources/tr02-1)) TR02.NEU.rovr.L1+L2 ([TXT](./resolveuid/c1d2a222013826d2b468d6da55c971aa)) TR02.NEU.rovr.LC ([TXT]({{< baseurl >}}/resources/tr02-neu-rovr))  
TR0p.sum ([TXT]({{< baseurl >}}/resources/tr0p)) TR0p.NEU.rovr.P1+P2 ([TXT](./resolveuid/f7c410edbea672c589d1296fb63a0d02))
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}
Applications, High-rate GPS results, and Tools ([PDF - 6.4MB]({{< baseurl >}}/resources/mit12_540s12_lec23))
{{< tdclose >}}
{{< tdopen >}}
Applications to tectonic problems  
Tools used to generate some of the figures  
[GAMIT/GLOBK MATLAB Tools](http://www-gpsg.mit.edu/~tah/GGMatlab)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}