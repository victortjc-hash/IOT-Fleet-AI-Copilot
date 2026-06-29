# IOT-Fleet-AI-Copilot
A solution mimicing IoT data into AWS IoT Core, stored in DynamoDB, displayed on Streamlit with AWS Bedrock AI CoPilot


 # Smart Fleet Health Copilot

An AI-powered fleet monitoring platform that simulates connected vehicle telemetry, streams data through AWS IoT Core using MQTT, stores telemetry in DynamoDB, visualizes fleet health in Streamlit, and uses Amazon Bedrock to provide natural-language fleet operations insights.

## Overview

This project demonstrates an end-to-end IoT and AI architecture for fleet health monitoring. Simulated vehicles publish telemetry such as GPS location, speed, engine temperature, battery voltage, fuel level, harsh braking events, and idle time. AWS IoT Core ingests the telemetry, an IoT Rule routes messages into DynamoDB, and a Streamlit dashboard displays vehicle health, risk status, maintenance priority, live map positions, and AI-generated fleet insights.

## Architecture

Vehicle Simulator
→ MQTT Publish
→ AWS IoT Core
→ IoT Rule
→ DynamoDB
→ Streamlit Dashboard
→ Amazon Bedrock Fleet Copilot

## Features

* Simulated multi-vehicle fleet telemetry
* MQTT publishing to AWS IoT Core
* Secure device authentication using X.509 certificates
* IoT Rule routing telemetry to DynamoDB
* Streamlit dashboard for fleet health monitoring
* Vehicle health scoring and maintenance risk classification
* Live fleet map using latitude and longitude telemetry
* Conversational AI Fleet Copilot powered by Amazon Bedrock Nova Lite
* Natural-language questions such as:

  * Which vehicle needs maintenance first?
  * Summarize the fleet health.
  * Which vehicles show overheating risk?
  * Why is this vehicle unhealthy?

## AWS Services Used

* AWS IoT Core
* AWS IoT Rules
* Amazon DynamoDB
* Amazon Bedrock
* IAM
* X.509 Certificates
* boto3
* AWS IoT Device SDK for Python

## Technology Stack

* Python
* Streamlit
* Pandas
* boto3
* AWS IoT Device SDK
* Amazon Nova Lite via Amazon Bedrock
* DynamoDB
* MQTT

## Business Value

This project shows how IoT telemetry and generative AI can support fleet operations by helping managers identify unhealthy vehicles, prioritize maintenance, understand operational risk, and ask natural-language questions about live fleet data.

## Future Enhancements

* Add AWS Lambda for cloud-side health score processing
* Add predictive maintenance using machine learning
* Add route history and geofencing
* Add alerting with Amazon SNS
* Add historical trend charts per vehicle
* Add executive daily fleet briefing
* Deploy dashboard to the cloud


<img width="1828" height="831" alt="Screenshot 2026-06-29 at 10 48 13 AM" src="https://github.com/user-attachments/assets/e0a44f7a-60d0-4f72-ab51-2a9b68dd4c52" />
<img width="1824" height="849" alt="Screenshot 2026-06-29 at 10 47 59 AM" src="https://github.com/user-attachments/assets/fefc7a77-a5f4-41d7-9282-3790507baf37" />
<img width="1851" height="777" alt="Screenshot 2026-06-29 at 10 47 45 AM" src="https://github.com/user-attachments/assets/32f4ce81-c2e8-4ae3-b906-c45206d027f4" />
<img width="1849" height="795" alt="Screenshot 2026-06-29 at 10 47 25 AM" src="https://github.com/user-attachments/assets/35d18f3b-0e3c-44e2-b736-666173fe141d" />






