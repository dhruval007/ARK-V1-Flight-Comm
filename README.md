# ARK-V1-Flight-Comm
ARK-1 is a custom-built flight computer designed for real-time data acquisition, navigation, and telemetry in aerospace applications. Powered by the ESP32-S3 microcontroller, it integrates multiple sensors and communication modules for accurate flight performance tracking and reliable ground-station communication.


Key Components:

MAX-M10S-00B (GNSS Navigation Sensor): Provides precise positioning and velocity data.

BMA400 (Accelerometer): Measures 3-axis acceleration for trajectory and launch analysis.

VEML6075 (UV Sensor): Captures UV index and radiation exposure during flight.

E32-900T30D (RF LoRa Module): Enables long-range telemetry link with ground station.

SHT31-DIS-B (Temperature & Humidity Sensor): Records environmental conditions inside and outside payload.

LIS2MDLTR (Magnetometer): Supplies orientation and heading data for attitude determination.

BMP390 (Pressure Sensor): Provides altitude estimation and apogee detection.

Core Functionality:

Onboard logging of sensor data for post-flight analysis.

Real-time telemetry transmission via LoRa RF.

Integrated flight logic for event detection (e.g., apogee, parachute deployment).

Modular design for expanding sensor payloads.
