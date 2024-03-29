# Tausand_AB1000_LabView8Library
Library and examples to use Tausand Abacus AB1000 devices with LabView 8.0 or later

This is a Plug and Play (project-style) library for LabView. To use it:
* Download the library.
* Extract the contents of the .zip file to a subdirectory of `<labview>\instr.lib`.
* Navigate to and open the .lvproj file. You can browse the examples included in the project to get started taking measurements with your instrument.
  
Help to use this library is found at National Instrument's tutorial: [How to Use an Instrument Driver in LabVIEW Tutorial](http://www.ni.com/tutorial/2804/en/)

## About Tausand Abacus AB1000

This is a family of coincidence counters, ideal to measure temporal correlations in particle detection and quantum optics experiments.

To learn more about them, visit our website www.tausand.com

To obtain a Tausand's Abacus coincidence counter, visit our [online shop](http://www.tausand.com/shop) or contact us at sales@tausand.com

## Tausand Abacus AB1000 Instrument Driver Readme

### 1. Overview
Instrument Driver Technology: LabVIEW Plug and Play (project-style)<br/>
Manufacturer: Tausand <br/>
Supported Language(s): LabVIEW <br/>
Supported Model(s): AB1002, AB1004 <br/>
Model(s) Tested: AB1002, AB1004<br/>
Interface(s): USB

Driver Revision: 1.1<br/>
Original Release Date: 06/17/2019 (mm/dd/yyyy)<br/>
Current Revision Date: 07/10/2019

### 2. Required Software
Some software components need to be installed before using this instrument driver. The minimum versions of these components are listed below, and can be downloaded from the Download Site.
* NI-VISA 15.0.1 or later
* LabVIEW 8.0 or later

### 3. Known Issues
To report issues or provide feedback about this instrument driver, please send an email to support@tausand.com.

### 4. Revision History
The latest version of this and other Tausand instrument drivers can be downloaded at Tausand downloads website.

* REV 1.0, 06/17/2019<br/>
Created by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
Original release.

* REV 1.1, 07/10/2019<br/>
Updated by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
Change on NI-VISA requirements to version 15.0.1 or later. Update on _Wait for Acquisition Complete_ VI. Now it returns a warning instead of an error when max timeout is reached. 
