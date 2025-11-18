# UiPath – Weather API Automation Workflow

This repository contains a **UiPath workflow** that demonstrates how to:
- **Fetch real-time weather data** using a public API  
- **Extract temperature, humidity, and conditions** from the API response  
- **Display results** in the UiPath output panel or Message Box  

---

## Project Overview
- Built using **UiPath Studio (Modern Design Experience)**  
- Demonstrates usage of **HTTP Request**, **Deserialize JSON**, and **Assign** activities  
- Perfect for learning **API integration** and **JSON parsing** in UiPath  

---

## Project Files
- `Main.xaml` → The main automation workflow  
- `project.json` → UiPath project configuration file  

---

## Workflow Logic

###  HTTP Request
- Sends a **GET request** to the **Weather API endpoint**, for example: https://api.openweathermap.org/data/2.5/weather?q=Chennai&appid=YOUR_API_KEY&units=metric
- Retrieves real-time weather data in **JSON format**.

### 🔹 Deserialize JSON
- Converts the JSON response into a readable UiPath object.  
- Enables easy extraction of nested fields like `main.temp`, `main.humidity`, and `weather[0].description`.

### 🔹 Assign / Message Box
- Extracts and displays key details such as:
- **City:** Chennai  
- **Temperature:** 30°C  
- **Humidity:** 70%  
- **Condition:** Clear sky  

---

## 🧩 Example Output
Weather Report

City: Chennai
Temperature: 30°C
Humidity: 70%
Condition: Clear sky

---

## Output
<img width="3855" height="2160" alt="Screenshot 2025-10-28 182604" src="https://github.com/user-attachments/assets/a279fba3-cfec-48bb-8401-68006bcc1cf1" />
<img width="3839" height="2157" alt="Screenshot 2025-10-28 182622" src="https://github.com/user-attachments/assets/83d829bf-c237-457b-822b-fd59b939441d" />
<img width="3839" height="2157" alt="Screenshot 2025-10-28 182648" src="https://github.com/user-attachments/assets/53b22885-1b03-486c-911b-591d7c97cbb4" />

---



