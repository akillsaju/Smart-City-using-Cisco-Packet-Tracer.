# Smart-City-using-Cisco-Packet-Tracer.

Aim

To design and simulate an intelligent urban environment in Cisco Packet Tracer that integrates: smart surveillance (CCTV/motion), intelligent street lighting (light + motion controlled), and fire monitoring (gas/temperature detection + alarm/notification). Demonstrate local automatic responses and centralized monitoring/alerts.

Problem statement

Cities need automated, low-cost sensing and response systems to reduce crime, save energy, and detect fires early. This project builds a simulated Smart City network that collects sensor data (motion, light, gas/temperature) and triggers actuators (street lamps, alarms, notifications) while recording and visualizing events centrally.

Scope

Simulate city network (routers/switches/APs) and Smart City IoT devices in Cisco Packet Tracer.

Simulate sensor & actuator circuits (Arduino/ESP + MQ-2, DHT11/TMP36, LDR, PIR, buzzer, relay) in TinkerCad.

Integrate Packet Tracer devices and external services via MQTT/Node-RED (demo of rules/automation).

Produce a demo video, Packet Tracer file, circuit diagrams, and source code.

Required components

Software

Cisco Packet Tracer (v7.x or v8.x) — for Smart City IoT simulation. 
Packet Tracer Network
SCIRP

Tinkercad (online) — for Arduino circuit simulation (MQ-2, DHT11, TMP36 examples). 
Tinkercad
+1

Arduino IDE (for real hardware)

Node-RED + Mosquitto (MQTT) for centralized automation & dashboard. 
Cisco DevNet

Git + GitHub account, OBS Studio (or other screen recorder) for demo

Hardware (if you implement physically later)

ESP32 or ESP32-CAM (camera & network) or Arduino UNO + Ethernet/WiFi module

MQ-2 gas/smoke sensor, DHT11/DHT22 or TMP36 (temp), LDR, PIR motion sensor

Relay module (to simulate lamp control), buzzer, LEDs, power supply
