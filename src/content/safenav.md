---
title: "SafeNav"
slug: "safenav"
client: "ESPE"
category: "Embedded Systems"
services: "Prototyping, Arduino-ESP32 Architecture, Bluetooth Audio"
year: "2024"
featuredImage: "./images/safenav/1.jpg"
imageTwo: "./images/safenav/2.jpg"
imageThree: "./images/safenav/3.jpg"
imageFour: "./images/safenav/4.jpg"
liveSite: "#"
description: "Smart assistive device for the visually impaired utilizing infrared sensors and Arduino-ESP32 processing to deliver real-time AI voice alerts."
isFeatured: true
isDraft: false
---

In Ecuador, approximately 11.54% of people with disabilities face visual impairment, highlighting a critical need for tools that foster autonomy. The challenge was to transform a conventional white cane into a smart assistive device capable of detecting physical hazards like obstacles or ground gaps in real-time. This project focused on creating a seamless, wearable-like experience that translates environmental sensor data into immediate, AI-generated voice alerts delivered via Bluetooth.

The technical architecture evolved through rigorous testing of hardware constraints. While ultrasonic sensors were initially considered, they lacked the precision required for safe navigation; thus, I integrated high-accuracy Sharp infrared sensors with a range of 20 to 150 cm. To handle the data processing and wireless transmission, I moved away from standard Arduino boards due to memory limitations, instead implementing a dual-microcontroller system using Arduino Nano ESP32 for processing and an ESP32 Devkit v4 to manage the low-latency Bluetooth audio stream.

This system prioritizes the user experience by converting complex sensor readings into intuitive auditory feedback. By overcoming the memory and processing barriers of traditional microcontrollers, the project successfully demonstrated a scalable, battery-powered solution for assistive mobility. It stands as a testament to human-centered engineering, where the choice of every component—from the laser sensors to the Bluetooth stack—is driven by the safety and independence of the end-user.