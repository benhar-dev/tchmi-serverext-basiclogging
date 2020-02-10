# Example using TcHMI with Server Extensions (creating server functions)

## Disclaimer

This is a personal guide not a peer reviewed journal or a sponsored publication. We make
no representations as to accuracy, completeness, correctness, suitability, or validity of any
information and will not be liable for any errors, omissions, or delays in this information or any
losses injuries, or damages arising from its display or use. All information is provided on an as
is basis. It is the reader’s responsibility to verify their own facts.

The views and opinions expressed in this guide are those of the authors and do not
necessarily reflect the official policy or position of any other agency, organization, employer or
company. Assumptions made in the analysis are not reflective of the position of any entity
other than the author(s) and, since we are critically thinking human beings, these views are
always subject to change, revision, and rethinking at any time. Please do not hold us to them
in perpetuity.

## Overview 

Simple demo to show the setup and configuration of a server extension which allows functions to be called upon it.

In this instance, calls are made to added symbol changes to the internal event logger. 

## Versions
This project uses the following

* Visual studio 2013/15/17 Community or Professional
* TwinCAT 3.1.4024.0
* TwinCAT HMI 1.10.1336.340

## Getting started

* Open the TcHmi project and open live view. 
* Trigger events at the bottom to see them reported to the server log

This is not a full guide for TcXaeShell, please visit http://beckhoff.com/ for further guides
