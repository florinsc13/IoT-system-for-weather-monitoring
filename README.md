# IoT-system-for-weather-monitoring


About the Project
This project proposes a modern and accessible smart weather station built from scratchThe central idea of this project is to realize a system that monitors the environment and reports the collected data, regardless of where the user is located. 

The architecture consists of a data acquisition node based on an ESP32 microcontroller that reads environmental parameters and transmits them wirelessly via a Wi-Fi networkThe data is published using the MQTT protocol due to its low latency and low resource consumptionA Raspberry Pi 4 is utilized as a local server and MQTT broker, storing the real-time data flow into a databaseUsers can view the environmental data through a dedicated web interface, removing the need to manually interpret raw values
<img width="945" height="285" alt="image" src="https://github.com/user-attachments/assets/4af32c6d-df3a-4c7c-a809-f9961a8ad706" />
<img width="945" height="646" alt="image" src="https://github.com/user-attachments/assets/12860189-d441-47d0-a0c2-d27d4f5e5f7d" />

