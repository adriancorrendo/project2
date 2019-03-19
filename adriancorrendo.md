# Calculate Yield Response to Variable Nitrogen Rates
---

**Name**: Adrian Correndo

**Semester**: Spring 2019

**Project area**: Agronomy

---

## **Objective**

Automatimg, for more than one experiment, the calculation of grain yield (GY) response to different rates of nitrogen (N) fertilizer, related fertilizer use efficiencies (NUE). For each experiment, also want the GY with no N added (Y0) and the maximum observed yield (Ymax).

## **Data example**

![Main steps of the project](https://github.com/adriancorrendo/project/blob/master/sketch.jpg)


## **Outcomes**

*.csv file with up to 8 columns: Trial, STx, Nrate, GY, Y0, Ymax, NR, and NUE, where:

**-Y0**: GY when Nrate=0;
**-Ymax**: maximum observed GY;
**-NR**: abs. nitrogen response corresponding to each fertilizer rate different from 0.

Challenge could be related to: 

i) Y0 and Ymax values are only one per Trial, while the NR and NUE values correspond to a sub-level identified by a given Trial-Nrate combination;

ii) Nrate levels (# and kg applied N) vary across trials. 

## **Rationale**

My research project will be related to managing a database of hundreds of corn nitrogen fertilization experiments. For this reason, automating the calculations will save me a significant amount of time when processing the data of nitrogen response, nitrogen use efficiency, and analyzing the database following a classification criterion to create subgroups of soil texture. Creating a criterion like the latter might be useful to reduce the number of potential groups of soil texture (12 main classes from clay to sand) and cluster them into, for example, three main subgroups (fine, medium, coarse).

