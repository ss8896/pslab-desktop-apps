---
layout: expt
title: Summing Junction
date: 2017-06-22
description: "Op-Amps: AC and DC Summing Junctions"
---

![](images/schematics/summing.svg){: width="400px"}


## DC Summing junction

Make the Connections as shown in the figure.

Use PV2, and PV3 as inputs. Connect them to CH2, CH3 to also simultaneously monitor them.

Monitor the output via CH1, and verify that V(CH1) = -(v1*(rf/r1)+v2*(rf/r2)), where

rf = feedback resistor
rf = input resistor
v1 = V(PV2)
v2 = V(PV3)

## AC Summing

Make the Connections as shown in the figure.
Use W1, and W2 as inputs. Connect them to CH2, CH3 to also simultaneously monitor them.
Monitor the output via CH1
Make the waveforms 180 out of phase, and check that they cancel each other out if the input amplitudes are equal
	

Observe various summing ratios by changing the input resistor values.

{% include summing_calculator.html %}

## Screenshot

![](images/screenshots/summing_junction.png){: width="700px"}

