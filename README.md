# RaspberryShake
Earthquake Data Processing from Raspberry Shake Seismographs

# REBOOT script for remote SSH
Script installed on raspberry pi computer board. Calls the device to keep searching for signal connection until found.
Ensures remote connectivity.

# SFTP for easy individual station data collection
Data collection can be done using the SFTP command. Must be done individually when using this process.

# SFTP data collecting from individual stations: 3 component seismographs
Using Pycharm, the SFTP data collection should be simple whether the network has 3 stations or 300 stations.
This script will be customizable for any number of stations with 3-component channels. 

# OBSPY data renaming convention compatible with PYTHON
Data collected from the RS-3D seismograph comes in MSEED format. 
Format is not readable in SEISAN. Must convert using ObSpy via Python.
