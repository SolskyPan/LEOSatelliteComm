# LEOSatelliteComm
Collect and decode the signals from weather satellites

## Satellite Signal Reception

### Devices 
RTL-SDR

USRP N210

### Softwares
Orbitron : Satellite Tracking App

SDRSharp : Signal reception app for RTL-SDR (here is a software that includes all the required plugins https://github.com/wikiZ/SDRSharpQPSK)

GNU Radio Companion (3.7 verison) : Signal reception app for USRP N210

### Satellites
NOAA series (FM modulation), e.g. NOAA 15/18/19/20

METEOR series (QPSK modulation), e.g. METEOR M1/M2/M2 2


## Satellite Signal Decoding

### Softwares
WXtoImg : decode the NOAA APT (Automatic Picture Transmission) signals, download link (stable verison) is: https://wxtoimgrestored.xyz/downloads/
LRPTDecoder: decode the LRPT (Low Rate Picture Transmission) signals, download link (LRPT Suite for Meteor M2 under Windows 7, 8 and 10) is: https://leshamilton.co.uk/MeteorLRPTSuite.htm, 
