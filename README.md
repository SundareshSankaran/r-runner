# r-runner
SAS Studio needs a quick and easy interface to R. This repository provides a custom step (a low-code component) which will enable developers to quickly submit R scripts from within SAS Studio (on SAS Viya) in a quick and no-nonsense manner.

And, yes! You guessed the inspiration behind the name correctly! :)

![R-Runner, beep beep!](/img/road-runner.jpg)

**Analytics developers appreciate unified interaction with SAS and R, especially in certain industries such as Pharma and Healthcare, which have significant R developers.  R-Runner helps such developers create solutions using R (as well as SAS and Python if required) within SAS Studio on SAS Viya.**


## A general idea

![Beep Beep](.)

## SAS Viya Version Support
Tested in Viya 4, Stable 2023.08


## Requirements

1. A SAS Viya 4 environment (monthly release 2023.04 or later) with SAS Studio Flows.

2. **At runtime: an active connection to CAS:** This custom step requires SAS Cloud Analytics Services (CAS). Ensure you have an active CAS connection available prior to running the same.

3. A SAS Visual Text Analytics (VTA) license. 

4. At least one Visual Text Analytics Model Studio project with a completed Categories or Concepts node.  Successfully running a categories or concepts node leads to the creation of system-generated rule configurations within a project caslib.


## Parameters:



### Input parameters:

1.


### Output specifications:

1. 

## Documentation:



## Installation & Usage
- Refer to the [steps listed here](https://github.com/sassoftware/sas-studio-custom-steps#getting-started---making-a-custom-step-from-this-repository-available-in-sas-studio).


## Created / contact : 

- Samiul Haque (samiul.haque@sas.com)
- Sundaresh Sankaran (sundaresh.sankaran@sas.com)


## Change Log

Version 1.0 (18AUG2023) 
* Initial Step Creation