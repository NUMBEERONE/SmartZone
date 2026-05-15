# Silent Zone IoT System

## Components
- ESP32 with microphone
- AWS EC2 with Mosquitto MQTT broker
- Node-RED flow for processing
- AWS Lambda + SNS for email alerts

## MQTT Topics
- silentzone/noise — noise level and state
- silentzone/traffic — traffic phase and countdown
- silentzone/penalty — violation events

## How to restore Node-RED flow
1. Open Node-RED
2. Hamburger menu → Import
3. Paste contents of flows.json
4. Deploy