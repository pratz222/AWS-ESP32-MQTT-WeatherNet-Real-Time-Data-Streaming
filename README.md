# AWS-ESP32-MQTT-WeatherNet-Real-Time-Data-Streaming

The **ESP32 WeatherNet** project facilitates real-time temperature and humidity monitoring through MQTT on Amazon AWS IoT Core. This innovative solution leverages the capabilities of the ESP32 microcontroller to collect environmental data and transmit it for analysis and visualization.

## Project Genesis

The motivation behind the ESP32 WeatherNet project stemmed from a need to monitor environmental conditions effectively and efficiently. By integrating an onboard temperature and humidity sensor with cloud capabilities, this project aims to provide users with accurate, real-time data for various applications.

## Distinguishing Features

### Sensor Integration
Utilizes an onboard temperature and humidity sensor, such as the DHT22, which connects seamlessly to the ESP32 microcontroller for reliable data collection.

### MQTT Communication
Data is transmitted securely to AWS IoT Core using the MQTT protocol, ensuring efficient and low-latency communication.

### AWS Integration
Leverages AWS IoT Core for data storage, processing, and visualization, allowing users to access and analyze their data easily.

## Hardware Setup

1. Connect the DHT22 sensor to the ESP32.
2. Ensure your ESP32 is connected to a stable Wi-Fi network.

## AWS Configuration

1. Create an AWS IoT Thing and generate security certificates.
2. Configure your ESP32 with the necessary credentials, including certificates and AWS endpoint.

## Code Deployment

1. Upload the provided Arduino sketch to your ESP32.
2. Update the Wi-Fi credentials and AWS endpoint in the code to match your setup.

## Data Monitoring

Monitor real-time temperature and humidity data directly on the AWS IoT Core dashboard, enabling comprehensive analysis and visualization of your environmental data.

## Dependencies

- Arduino IDE
- Adafruit DHT library (for sensor communication)

Feel free to reach out for any queries or contributions! Happy monitoring with **AWS-ESP32-MQTT-WeatherNet**!

![AWS MQTT Dashboard](https://github.com/user-attachments/assets/420692fa-9508-4fe4-9f18-5d84cf15dda2)

