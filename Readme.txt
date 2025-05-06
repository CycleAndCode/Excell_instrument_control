Intro:
An universal communication script framework executing one-by-one commands organized in an Excel sheet
Compatible device:
* almost all kinds of devices communicating over various interfaces like GPIB, RS232, Ethernet, USB and other which can be properly recognized in NI-MAX as VISA resources
Features:
* simple data logging and testing of device interfacing
* test sequence synchronisation with multiple devices
* logging of interface response
* script input selectable as Excel sheet or .txt
* ability to call subscripts from the main script
* ability to parametrize subscripts (calling and parametrizing subscripts makes it possible to call them like functions)
* PAUSE function to wait for a manual action
* exporting scripts to .txt format 
* Implemented special higher level functions:
*** preprogrammed communication with BMD via diagnostics frames (required for BMD functional test)
*** supports BURSTER 4462 voltage calibrator communication
*** supports GW INSTEK GPT-9000 series ACW up to fail test over a settable range of voltage steps
*** ability to call every executable (.exe) program like from command line with parameters
Applicable to:
* creating test sequences
Hints:
* If Excel is not activated on the target computer, the program may stuck trying to open the Excel file. In such scenario, install the program on a computer with Excel, and run it (no hardware, VISA or 488.2 required) with "Save script as .txt" enabled. You can then move the .txt script to the target computer and run the program with this script.
* There is also a dedicated "Rebuild_script.exe" for this specific purpose
* "POŁĄCZ.TEKSTY" in Excel
* Remember to enable Keysight GPIB interfaces for non-Keysight programs.
System requirements (all free downloadable):
* LabVIEW RUNTIME Engine 2019 - 32bit    (exact this version)
* NI-VISA (almost all versions should work)
* NI-488.2
* MS Excel
