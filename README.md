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

---

### 🔧 How to Run This Logic App

1. Open Azure Portal → Create a new Logic App (Consumption or Standard).
2. Go to Code View → Paste content from `logicapp-workflow.json`.
3. Set your API key, city name, and email in the correct fields.
4. Save and test the workflow.
