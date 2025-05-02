# Hamilton-NGS-Star-workstation-in-solution-hybridization-capture
## About

This repository contains the electronic protocol files for the automated TWIST hybridization capture of ancient DNA libraries on the Hamilton NGS Star in 96-well format for up to 384 samples at once. 

This repository also includes electronic protocol files for

+ preparation of the sample plate (384 format)
+ boiling of up to 4 96-well bead plates for qPCR quantification
+ qPCR quantification of capture yields for 2 96-well plates at once

## Requirements

To use the protocols, two Hamilton NGS Star systems with custom deck layouts are required. Calibration of the instruments for these protocols have to be performed by the user and requires significant expertise in using the platform.

## Implementation and Documentation

+ Use Hamilton Method Editor to import package files: method, device file, sub-methods, files and liquid classes. (Import Mode: Recovery.)
+ liquid_classes_in_solution_capture.mdb can be used to overwrite existing liquid classes. (Should be imported by the Hamilton Method Editor while importing the pkg file.)
+ MailAlert.zip can be installed to enable the system to send Mails for errors or other notifications.
+ Espacially in the 384 TWIST method we have a high tip throughput. We recommend using a Cytomat (Thermo Scientific). We added a folder for installing the Cytomat driver to your system after implementing hardware onto your system.

## References

tbd
