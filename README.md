# ESP32 Based Board Design
#### Client: Ridvan Bozkir

## Project Requirements
The project consists of two boards:
1. Main Board
2. Sensor Board

### Main Board Requirements
- Based off of ESP32 module and related circuitry (most easily and in good stock on JLCPCB).
- Backup battery to ensure data is not lost in case of power outage.
- The board should also have other peripherals as present in attached images below. The only two additions / modifications are mentioned in above two points.
- Preference to make the battery rechargeable as well but only if the size doesn't increase because casing is prepared for Main Board. Step file for main board casing is pushed to project docs.
- The full design should be made through JLCPCB.
  
#### Existing Main Board Design
![image](https://github.com/user-attachments/assets/4db5652d-abb2-4443-b199-4bcd67bbb56e)
![image](https://github.com/user-attachments/assets/581cfd20-f243-41f9-99fa-9997d1278a42)


### Sensor Board Requirements
- Each sensor board will use the TLSR8250F512ET32 microcontroller. This selection is open to suggestions however. Only the most feasilbe, compact and power friendly must be selected.
- The SHTC3 will be used as the temperature sensor.
- The sensors will be powered by a CR2477 battery. This selection is open to suggestions however. Maximum backup in minimum size is preferred.
- The casing files are present in docs. Circuit selection should be done accordingly.

#### Existing Sensor Board Design
![image](https://github.com/user-attachments/assets/c154cfd3-983f-450a-9d9e-de15547e6475)
![image](https://github.com/user-attachments/assets/dc2ff387-c879-4d14-935a-a552dd4f0289)
