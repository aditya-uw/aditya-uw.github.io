---
title: WeatherPatrol
summary: 'A TinyML Rain Prediction System using the Arduino Nano 33 BLE'
tags:
- Machine Learning
- Research
- Class Projects
date: "2024-06-04T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ''
  focal_point: Smart

# Display this page in the Featured widget?
featured: true

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Description:

The EE 400 TinyML course taught by Professor Radha Poovendran was a fantastic opportunity to study embedded machine learning and become acquainted with several applications in the rising field of TinyML to develop smart edge devices capable of doing on-board inference. My partner, [Pujan Patel](https://www.linkedin.com/in/pujan-patel-0535a1217/), and I decided to develop a rain prediction system using the Arduino Nano 33 BLE to read low-cost environmental variables such as temperature, pressure, and relative humidity and predict the occurence of rain in the coming period. 

We prototyped this project into the deployment stage where we used rechargeable batteries along with a weatherproof box to deploy our system on a tree where it would transmit Bluetooth Low-Energy (BLE) notifications to connected smartphones on whether it would rain in the next 30 minutes.

### Materials:
- Arduino Nano 33 BLE
- BME680 environmental sensor
- LightBlue app on smartphone
- Weatherproof box, rubber cord, and rechargeable batteries

### GitHub Repository: 
https://github.com/aditya-uw/WeatherPatrol

### **[Project Slides](./presentation.pdf)**

### Acknowledgements:
I want to first thank my partner Pujan Patel for helping me develop this project. I also want to thank Professor Poovendran for teaching a fantastic course reviewing the many applications and fundamentals of TinyML. Finally, I want to thank the ECE department for providng reimbursements for the expenses of our project.
