# Project Title: Attenuation of Waves in Sea Ice in the Arctic Ocean During Autumn Freeze-Up
## Names: Maddie Kimmel and Sabrina Sandburg 

## Project Summary: 
Climate change is reshaping polar environments, delaying Autumn freeze-up of sea ice by over two months and causing a greater shift from perennial to seasonal sea ice. Sea ice has historically been a guard for Arctic coastlines by reducing wave energy and warding off erosion and storm surge. However, the coevolution of strengthened Autumn Storms due to increased sea surface temperatures and decreased presence of sea ice, coastal habitats and local communities who are at risk. This project seeks to understand the dynamics between waves and sea ice by calculating wave attenuation rates in the marginal ice zone.
## Background: 
### What is Wave Attenuation? 
Wave attenuation is the loss of energy as waves travel through a medium. As ocean waves propagate through sea ice, they attenuate or lose energy due to higher friction imposed by the ice. When observed, shorter wavelength waves quickly die out, whereas longer gravity waves attenuate but continue to propagate through the ice.
Visual Aid: https://www.youtube.com/watch?v=CU2xz8F-PLE

### How to Calculate Wave Attenuation?
Wave attenuation is typically modeled using an exponential decay, with alpha representing our attenuation rate. We will be using wave height as a proxy for wave energy in this project, as they are proportional to one another. We will use Equation 1 from Thomson et al. 2021 to complete our calculations, where x is the distance crosshorse. 
          
# $H(x) = H_0 e^{\alpha x}$

### Pancakes? Frazil? What do the different types of Ice Mean? 
The typical (and highly simplified) evolution of sea ice formation is: frazil ice, which has a slushie-like consistency, thickens and develops into pancake ice— think American-diner-size circular ice floes that eventually clump together to form ice rafts. These rafts continue to consolidate and combine to form larger ice sheets, and eventually ice bergs. For the purposes of this project, we will be focusing on how waves interact with newly formed frazil and pancake ice. Reference Below Sea Ice Code Chart created by Cal Hobson:



### Study Site: 
For this study we will be examining a three day wave event at the S1 Mooring Site from November 21-23,2019 as part of  CODA (Coastal Ocean Dynamics in the Arctic) 2019 project. During this event, a sustained 2m wave height was observed with a maximum of 3m significant wave height. Wave attenuation was also observed as waves passed through the ice edge, as wave height decreased as waves traveled inshore and further into the sea ice. Additionally, the type of ice observed at the site also changed during the wave event, starting with pancake ice transforming to frazil/grease ice and converting to open water by the end of the wave event. However the decrease in sea ice was probably due to the transportation and mixing of ocean heat nearshore from the wind and waves (via Stokes Drift). 

<img width="623" height="378" alt="Screenshot 2026-02-13 at 11 27 45 AM" src="https://github.com/user-attachments/assets/600bf04f-55e9-4b89-9904-5873e0076eb9" />

*Map of Mooring Sites for the CODA 2019 Research Cruise*


## Objectives: 
- Define a coordinate system of the crossshore S1 Moorings
- Determine where the Marginal Ice Zone is as a function of time as it evolves during Autumn Freeze-up 
- Calculate Wave Attenuation Rates in Marginal Ice Zone using Wave Height based off of Ice type 

## Datasets: 
- S1 Mooring Site Data from the CODA (Coastal Ocean Dynamics in the Arctic) 2019 Research Cruise: https://digital.lib.washington.edu/researchworks/items/4402d31c-6c46-4c2b-be01-2fa63896fbe1
- Cruise Data (probably will not use but included just in case): https://www.rvdata.us/search/cruise/SKQ201923S

## Tools/Packages to Use: 
- SWIFT toolbox:
    https://github.com/SASlabgroup/SWIFT-codes/tree/e02b0498f46343abb6897720519d1ae3c114f7c4/Python
- Jake Davis PHD wave functions:
    https://github.com/jacobrdavis/ocean-surface-wave-slopes-and-wind-wave-alignment.git
- Wave Spectra Package:
    https://github.com/wavespectra/wavespectra.git

## Methodology:
Determine Location of Marginal Ice Zone and how it evolves over the study period 
Create a Coordinate System where x has a dependence on ice and perpendicular to the ice edge 
Calculate the Wave Attenuation Rate as a function of Wave Height using Equation 1 from Thomson et al 2021. 
## Expected Outcomes:
First, we expect to produce a set of graphs that show a decrease in the wave heights in the x direction as they travel from open water, through the ice covered region. Secondly, we expect to produce a graph that shows a positive correlation between the thickness of the ice and the extent to which incoming waves are attenuated.

## References:
https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2020GL090735
https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020JC016746


