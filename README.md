# Sigma-Chi-Website
A website to perform Kernel Density Estimations and display their graphical representations while out on the field. Developed for Dr. Christopher Spencer, Head of Geology Department at Queen's University. _The website application is currently being hosted exclusively for Queen's students, however I provide substantial photos in this documentation and a live demo is available by downloading the project files in this repository._

**Table of Contents**

-  [Purpose](#purpose)
-  [Description](#description)

## Purpose

One of the main problems faced by students in Dr. Christopher Spencers geology classes was that they were unable to efficiently collect and interpret the data that they were looking at while out on field studies. The purpose of this application is remedy this situation, to allow students to save data locally to their device, perform statistical calculations, and graph these calculations to see trends in real time.
## Description

![image](https://github.com/Pryzux/Sigma-Chi-Website/assets/33528419/2eb49a90-5cda-4db8-b229-1bc0641cb821)



This application can perform Kernel Density Estimations under either the Gaussian or Epanechnikov functions. Here is a breakdown of all the configurable settings for the calculations:

**Evaluation Settings**

![image](https://github.com/Pryzux/Sigma-Chi-Website/assets/33528419/c3fb5389-1f96-4451-b294-fffe53b4203a)

**Data Input || Export**

To input data, You can either input an excel data spreadsheet or manually input the data, which is then cached in the web browser.

![image](https://github.com/Pryzux/Sigma-Chi-Website/assets/33528419/71d2a18e-f748-4328-8111-e8da15ba0ee0)

To export the data, click the export button and choose to export 1) the data you have collected 2) the graphs created 3) or both 1 & 2.

![image](https://github.com/Pryzux/Sigma-Chi-Website/assets/33528419/f552d569-5024-4095-856a-be300fb5905e)

**Example**

If you would like to try the web application for yourself but do not have the required data, please feel free to use the test data provided:

**Data Uncertainty:** 1 sigma

**Data Rejection:** no rejection

**Data:** 23, 3, 22, 14, 14, 4, 14, 8, 9, 16, 13, 20, 16, 12, 14

**uncertainties:** 2, 3, 2, 4, 2, 0, 2, 4, 3, 0, 1, 0, 1, 3, 0

**AllData:** (3, 9, -3)(4, 4, 4)(8, 16, 0)(9, 15, 3)(12, 18, 6)(13, 15, 11)(14, 22, 6)(14, 18, 10)(14, 18, 10)(14, 14, 14)(16, 16, 16)(16, 18, 14)(20, 20, 20)(22, 26, 18)(23, 27, 19)

**Weighted Mean:** 12.407407407407407

**Weighted Mean Variance:** 32.56025867136978

**Weighted Mean Uncertainty:** 1.473324102641592

**kernel density y:** 0.00004926905833638443, 0.0018405145779965496, 0.017326446822421123, 0.04745026731701892, 0.047450584220769566, 0.01737571588058087, 0.0036810291561697227, 0.017375716366828182, 0.047450901611474035, 0.047499538319637845, 0.019168229016480062, 0.01936277099001868, 0.05466641939131234, 0.10968802612421591, 0.14857110188430173

**Expected Value (used in chi squared):** 13.466666666666667

**Chi Squared:** 161686867806876380, 197684.57643110698, 88858434582678940, 201959414707416.9, 201959414707416.9, 9516584.456192974, 201959414707416.9, 107733734468.10997, 526266449017.78174, 1219613780119630, 74446399868030.73, 24619382995105624, 1219613780119630, 25334597159550.64, 201959414707416.9

**Reduced Chi Squared:** 10779124520458426, 13178.9717620738, 5923895638845263, 13463960980494.46, 13463960980494.46, 634438.9637461982, 13463960980494.46, 7182248964.540665, 35084429934.51878, 81307585341308.67, 4963093324535.382, 1641292199673708.2, 81307585341308.67, 1688973143970.0427, 13463960980494.46

**Kernel Median:** 14

**Kernel Mode:** 14

