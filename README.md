This project demonstrates the design and implementation of a complete environmental monitoring system based on Zigbee wireless sensors, a Zigbee coordinator, and a MQTT-based data pipeline.
It integrates the Sonoff SNZB-02 temperature & humidity sensor with the Sonoff PGM24 (EFR32MG24) Zigbee coordinator, and uses Zigbee2MQTT together with a MQTT broker to acquire, process, store, and visualize environmental data in real time.

The goal of this project is to provide a fully functional IoT data acquisition chain, from the physical Zigbee network to the digital backend, demonstrating how low-power sensors can communicate with a central system through standard protocols.
It also shows how the data can be consumed by user applications (Python, dashboards, web clients, etc.), making the system suitable for educational, prototyping, or pre-industrial use
Modern IoT systems rely on low-power wireless networks for environmental monitoring, automation, and smart-building applications. Zigbee technology is widely adopted due to its low energy consumption, mesh capabilities, and reliability in indoor environments.

In this context, the Sonoff SNZB-02 is a consumer-grade sensor capable of periodically reporting temperature, humidity, and battery status. The Sonoff PGM24 acts as a Zigbee Coordinator based on the Silicon Labs EFR32MG24 radio chipset, providing a stable and powerful backbone for a Zigbee network.

The project focuses on integrating this hardware with an open-source middleware for IoT interoperability:

Zigbee2MQTT for decoding Zigbee frames and exposing them through MQTT topics

Mosquitto MQTT broker for message routing

Custom scripts (Python, Bash) for data processing and analysis

Optional web dashboard for visualization


By Alexis AGGEY
