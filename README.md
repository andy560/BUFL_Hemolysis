# BUFL_Hemolysis

- Use Load_Cell_Read and run serial monitor through CoolTerm app in order to save serial monitor as .txt file (https://freeware.the-meiers.org/). Load_Cell_Run will output raw load cell value, weight value based on calibration, and a timestamp. 

- Upload .txt file to TXTreader in MATLAB to read values and plot graphs.

Instructions for TXTreader
  - Enter given values
  - Choose file
  - Choose range to tare force. If no tare is needed, enter -1 for start and end x values.
  - See Graph for volumetric average of flow rate for each vial
