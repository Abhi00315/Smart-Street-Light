# Intelligent Street Lighting System with Fault Detection

This project presents a design for an **intelligent street lighting system** that incorporates automatic fault detection and efficient monitoring of streetlights. The system is built to optimize energy usage, streamline maintenance, and ensure reliable operation.

## Features

1. **Intensity Control**
   - Adjusts streetlight brightness based on environmental conditions to improve energy efficiency.

2. **Sensor Integration**
   - **Ultrasonic Sensors**: Detect objects and manage streetlight activation.
   - **LDR Sensors**: Measure ambient light intensity to control lighting functionality.

3. **Microcontroller-Based Design**
   - Utilizes the **ESP32 microcontroller**, which is cost-effective, low-power, and equipped with Wi-Fi for data storage and remote monitoring.

4. **Maintenance Tracking**
   - **RFID Tags**: Each streetlight is associated with an RFID tag to track maintenance activities. Logged data is stored in a centralized database for easy management and analysis.

5. **Operational Status Monitoring**
   - Combines **voltage sensors** and **LDR sensors** to provide real-time insights into:
     - Power supply integrity.
     - Lighting functionality.
   - Enables quick detection and resolution of faults.

## Objectives

- Enhance the efficiency of street lighting systems.
- Reduce energy consumption through intelligent intensity control.
- Simplify maintenance and fault detection with advanced monitoring tools.
- Promote sustainable and reliable urban infrastructure.

## Components Used

- **ESP32 Microcontroller**
- **Ultrasonic Sensors**
- **LDR Sensors**
- **Voltage Sensors**
- **RFID Tags**
- **Wi-Fi Connectivity for Data Logging**

## Applications

This system is ideal for smart cities, enabling smarter and more sustainable urban infrastructure. By integrating modern technology, it ensures reliable, efficient, and easily maintainable street lighting solutions.

## Future Improvements

- Integration with IoT platforms for advanced analytics.
- Use of renewable energy sources for powering streetlights.
- Predictive maintenance using machine learning algorithms.

---

### Deployment

The system is deployed and hosted on Firebase. Access the live application using the link below:  

**[Website Link](https://street-light-iot-76576.web.app/)**

Follow these steps to deploy the system using Firebase:

1. **Install Firebase CLI**:
   npm install -g firebase-tools
2. **Initialize Firebase:**:
   firebase init
4. **Login to Firebase:**:
   firebase login
6. **Deploy the Application:**:
   firebase deploy
