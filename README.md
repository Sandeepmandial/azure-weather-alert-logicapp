# 🌦️ Automated Weather Alert System using Azure Logic Apps

This mini project demonstrates how to build an **automated weather alert system** using **Microsoft Azure Logic Apps**. It fetches real-time weather data from the **OpenWeatherMap API**, checks for specific weather conditions like thunderstorms or extreme temperatures, and **sends alerts via email or SMS**.

> 🔁 The workflow is completely automated and runs on a set schedule (e.g., every hour).

---

## 📌 Features

- Fetches real-time weather data for a specific city
- Parses and checks conditions (e.g., Thunderstorm, Rain, High Temp)
- Sends alerts through Outlook Email or Twilio SMS
- Logs weather data into an Excel sheet (via OneDrive)
- Scalable and customizable for different cities or alert types

---

## 🛠️ Tools & Technologies Used

- **Microsoft Azure Logic Apps**
- **OpenWeatherMap API**
- **Outlook Email (Office 365)**
- **Twilio SMS** (optional)
- **HTTP GET Request & JSON Parsing**
- **Excel via OneDrive (for logging)**
