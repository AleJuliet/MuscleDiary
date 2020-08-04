# MuscleDiary

This is an Android Application made for the course Personal Data Interaction from the Technical University of Denmark (DTU).

Developed in March-June 2018

## Installation
- Clone this repository and import into **Android Studio**.
- The project imports Shimmer API.
- This app is configured to be used together with a Shimmer sensor http://www.shimmersensing.com/products/shimmer3-emg-sensor


## Structure
### Main screen:
After conecting with Shimmer sensor, user selects the muscle to measure

![alt text](https://github.com/AleJuliet/MuscleDiary/blob/master/readmefile/firstscreen.png?s=300)

## Results screen
This screen shows the results of the measurement, which takes around 1 minute

![alt text](https://github.com/AleJuliet/MuscleDiary/blob/master/readmefile/secondscreen.png?s=300)

The information displayed are:
- EMG signal vs time graph (The Simple moving average algorithm was used to process data)
- Active training
- Maximum amplitude 
- Mean amplitude

![alt text](https://github.com/AleJuliet/MuscleDiary/blob/master/readmefile/thirdscreen.png?s=300)

## History
The result are recorded, and therefore can be visualized in the history screens (this is not fully implemented yet)

![alt text](https://github.com/AleJuliet/MuscleDiary/blob/master/readmefile/fourscreen.png?s=300)
