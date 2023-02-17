---
layout: post
title: SOP-8 Jellybean Buck Converters. 
subtitle: Let say goodbye to the LM2596, LM2576 and co.  
tags: [electronics]
comments: false
---


Modern DC-DC Converter offer higher performance than ever before, and thus often come in complicated, optimized packages unique to that IC. 
When high performance is not requires for example for a hobby project or some generic product it is a good idea to design with alternative components in mind. 
Especially during this component crisis. So called jellybean parts are components which are manufactured by a bunch of vendors offering a common package and at least similar performance. A example of this is the LM317 or the 780x, 1117 series. 

In the World of DC-DC converters the LM2596, LM2576 as well as other older parts of Texas Instruments Simple Switcher have become such Jellybean parts. 

Unfortunately they come in rather bulky TO-220 or TO-263 packages, are non syncronous which means they need a external rectifier diode and have a low switching speed. 
For my designs I wanted a smaller buck converter with a higher switching speed which improves efficency and allows for smaller inductor and capacitor, further it improves the load response. While there are a bunch of converters available in SOT23-5 or SOT23-6 packages they are less suited for high currents over a longer period of time due to the higher thermal resistance, thus I chose the SOP-8 package with a large "Ground Pad" which transfers heat more easily. 

| Vendor | MPN |
|---------|---------|
| MPS   | MP2307  |
| MPS   | MP1484  |
| HTCSEMI  | HT2307A  |
| Richtek  | RT8293A  |
| axelite | AX3484  |
| EUTECH | EUP3484  |
| Fitipower | FP6193  |
| Techcode | TD2786  |
| Diodes Inc. | AP6502  |  
| Diodes Inc. | AP6503  |
| Diodes Inc. | AP3503E  |
| Richtek | RT7257E  |
| Anpec | APW7301  |
| AME | AME5268  |
| MaxLinear | XRP7664  |
| MaxLinear | XRP7665  |
| Texas Instruments | TPS54336A  |
| Joulwatt | JW5025  |


JW5025



