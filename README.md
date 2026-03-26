# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server

### NAME : M.YOGASRI
### REG NO: 212224220124
### DATE : 09/03/2026
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1364" height="713" alt="image" src="https://github.com/user-attachments/assets/5a41bf1f-faff-4f95-8d5a-8fc3c4a1396f" />
<img width="1364" height="716" alt="image" src="https://github.com/user-attachments/assets/2cff4e65-a275-4273-9cfc-bfdde29fcbf9" />

### 2. Network Server – Recent Events
<img width="1919" height="1019" alt="Screenshot 2026-03-16 155740" src="https://github.com/user-attachments/assets/dc859d10-cb1b-46b3-ba01-08e168bb555e" />
<img width="1919" height="1038" alt="Screenshot 2026-03-16 155904" src="https://github.com/user-attachments/assets/116a0ab0-f2af-49c0-95dc-d016abfa6997" />


### 3. Dashboard Command Sending
<img width="1919" height="1020" alt="Screenshot 2026-03-16 155751" src="https://github.com/user-attachments/assets/f2d37a7a-8fd2-42d8-9543-e0177f0651f5" />
<img width="1908" height="1018" alt="Screenshot 2026-03-16 155846" src="https://github.com/user-attachments/assets/628e397b-98e4-461a-bce5-fce0df297c23" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1280" height="570" alt="image" src="https://github.com/user-attachments/assets/68a7225b-5d4a-44c4-8b6f-4becb2c06ebe" />

### Bulb OFF → Relay OFF
<img width="570" height="1280" alt="image" src="https://github.com/user-attachments/assets/e35bdff3-3a44-4e42-a82b-95ec10dc16e5" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
