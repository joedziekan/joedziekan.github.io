---
title: "Fairbanks Morse Engine Internship June-August 2018"
date: 2018-08-28
tags: [Engineering Experience]
author_profile: false
header:
  image: "/images/FME.jpg"
excerpt: "Research and Development Intern: Lubrication Oil Pump Project"
---
**Overview**

I worked in the Research and Development department on projects directly related to the [Trident Opposed Piston Engine](https://www.fairbanksmorse.com/trident-op). These projects consisted of conducting a failure analysis of an emissions testing probe before redesigning it, speeding up the startup of the engine, and creating a piston assembly cart to help technicians put in and take out pistons.

**Analysis of Lubrication Oil System for possible redesign**

*Situation*

The engine startup time (190 seconds) is limited by the pressure experienced by the lubrication oil pump. The lubrication oil is thicker at the heater temperature initially so the engine needs more time to warm up the oil to decrease its viscosity. However, the pressure limit is in place to prevent the lubrication oil idler shaft (as seen below) from shearing due to immense stress. There has been a history of failures in these shafts and the Research and Development team at FME wanted to know if the shaft can be pushed past the pressure limits put in place without failing in order to achieve an engine startup time of 30 seconds.

<img src="{{ site.url }}{{ site.baseurl }}/images/Shaft.png" alt="Idler Shaft">

*Task*

 I was tasked with investigating these failures and analyzing the possible failure in the lubrication oil system with our given testing conditions.

*Action*

I began with an analysis of the idler shaft during power transmission to determine the boundary conditions caused when the engine was running. The shaft was conceptualized to undergo constant loading once the engine was idling. Then, an Excel model was created to calculate these boundary conditions when varying startup time. A finite element model (seen below) of the idler shaft was then created in SolidWorks to analyze the stresses caused by the boundary conditions. As a result, the shaft was determined to be safe at the new startup time in respect to failing immediately due to loading. Next, the failure of the shaft due to fatigue at the new startup time was then analyzed, and found to be within the infinite lifespan of the shaft. To verify this calculation, I worked directly with a mechanical testing company to send an extra idler shaft out to be tested for fatigue due to torsion.

<img src="{{ site.url }}{{ site.baseurl }}/images/fea.png" alt="Idler Shaft FEA">

In addition to the idler shaft, the reduced startup time of the engine could also cause the failure of the two water pump shafts being driven off of the crankshaft gear as well. The crankshaft gear transmits power from the crankshaft gear to the lubrication oil pump and two water pumps. This gear uses torsional spring dampers to prevent chattering between the gear teeth, however, these springs may be compressed to the full extent if the startup time is reduced. If this occurs, the torsional vibrations could cause the water pump and/or lubrication oil pump shafts to shear. Therefore, design recommendations were made to prevent this crankshaft gear from torsional vibrations. At the end of my internship, a model for the water pump shafts under loading was still in the process of being created.

*Result*

The Research and Development team at Fairbanks Morse Engine have recommendations to improve the design of the idler shaft, crankshaft gear, and water pump shafts.



*Results*
