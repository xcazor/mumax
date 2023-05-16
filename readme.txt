This repository is made up to organize the results of simulations made in mumax3.
In this repository you will find four folders:
-default
-dmi
-drill
-isolated 

--standard: 
This is the STT term of LLG equations without DMI, applied to a vortex initial magnetization state. 
In this folder you will find: 

-STT standard code: 
-Variations for the A exchange energy (high, low, zero, negative)
-Variations for the Js current

--dmi: 
This is the STT terms of LLG equations with DMI, applied to a vortex initial magnetization state. 
In this folder you will find: 

-STT dmi code: 
-Variations for the A exchange energy (high, low, zero, negative)
-Variations for the Js current (high, low, zero, negative)
-Variations for the Dbulk (high, low, zero, negative)
-Variations for the anisU (high, low, zero, negative) 

--drill:
test codes, when we are using new propeties, or blending codes, unformaliced but working codes. 

--isolated: 
This is the STT term of the LGG equation, which ideally each term isolated in the LLG.
Given the three terms with mumax3 works (Larmor, Gilbert, STT), this three terms, where 
applied to a vortex initial magnetization state. 
Then in this case we will have: 
-Isolated: without damping, and without STT or Jc current. 
-Damping: with damping, and without STT or Jc current. 


