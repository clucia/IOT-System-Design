# Requirements

System Design Question: IoT Sensor Data Logger

Problem Statement:You are designing an IoT-based telemetry data logger for a smart industrial monitoring system. The system must:

Collect sensor data from multiple sources (e.g., temperature, humidity, pressure, and vibration sensors).

Efficiently store sensor readings in a circular buffer to prevent memory overflow.

Transmit data to a cloud server at scheduled intervals.

Send immediate alerts for critical events (e.g., high temperature, abnormal vibration).

Prioritize data transmission:

High-priority alerts must be sent immediately.

Regular telemetry data should be sent in batches to conserve network bandwidth.

Requirements & Constraints:

The device runs on a low-power microcontroller with limited RAM and CPU.

It uses wireless communication (e.g., Wi-Fi, LTE, or LoRa) to transmit data.

The system must gracefully handle network failures (e.g., store data and retry transmission).

The design should be modular, allowing future integration of new sensor types.

Please describe how you would design and implement a system that meets the above requirements and adheres to the given constraints.