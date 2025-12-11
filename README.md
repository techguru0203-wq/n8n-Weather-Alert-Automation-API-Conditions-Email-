# n8n Automation — Weather Alert System

This workflow calls the OpenWeather API, checks if the temperature  
exceeds a threshold, and sends an alert email.

---

## 🚀 Workflow Summary
1. Manual Trigger  
2. HTTP Request (Weather API)  
3. Extract temperature  
4. IF condition (temp > 30°C)  
5. Send alert email  

---

## 📂 Project Structure
```text
n8n_weather_alerts/
├── workflows/
│ └── workflow.json
├── docs/
│ └── sample_output.json
└── README.md
```

---

## 🔧 Setup
- Insert your OpenWeather API key  
- Configure email credentials  

---

## 📜 Notes
Great example of API automation + conditional triggers + notifications.

---

**Notes**
- Replace the HTTP Request node's API key placeholder with a valid OpenWeatherMap API key.
- Configure the Email node with your SMTP credentials or use an Email node credential in n8n.
