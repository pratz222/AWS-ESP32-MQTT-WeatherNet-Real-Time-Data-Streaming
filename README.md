# AWS-ESP32-MQTT-WeatherNet-Real-Time-Data-Streaming
ESP32 WeatherNet: Real-time temperature and humidity monitoring via MQTT on Amazon AWS IoT Core.

Overview:

The ESP32 AWS IoT Weather Monitoring project enables real-time temperature and humidity data collection using an ESP32 microcontroller. The data is transmitted via MQTT to Amazon AWS IoT Core for further analysis and visualization.

![AWS MQTT Dashboard](https://github.com/user-attachments/assets/420692fa-9508-4fe4-9f18-5d84cf15dda2)

Features:

Sensor Integration: Utilizes an onboard temperature and humidity sensor (e.g., DHT22) connected to the ESP32.
MQTT Communication: Data is securely transmitted to AWS IoT Core using the MQTT protocol.
AWS Integration: Leverages AWS IoT Core for data storage, processing, and visualization.

Hardware Setup:

Connect the DHT22 sensor to the ESP32.
Ensure your ESP32 is connected to Wi-Fi.

AWS Configuration:

Create an AWS IoT Thing and generate security certificates.
Configure your ESP32 with the necessary credentials (certificates, endpoint, etc.).

Code Deployment:

Upload the provided Arduino sketch to your ESP32.
Update the Wi-Fi credentials and AWS endpoint in the code.

Monitor Data:

View real-time temperature and humidity data on the AWS IoT Core dashboard.

Dependencies:

Arduino IDE
Adafruit DHT library (for sensor communication)


