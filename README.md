# 🌡️ IoT DHT11 Sensor to MQTT Dashboard using Raspberry Pi

This project reads temperature and humidity values from a **DHT11 sensor** connected to a **Raspberry Pi** and publishes the data to the **HiveMQ public MQTT broker**. The real-time data is then visualized on an **open-source IoT dashboard**.

---

## 🧰 Components Used

- Raspberry Pi (any model with GPIO)
- DHT11 Temperature & Humidity Sensor
- IoT Development Trainer Board (Model: PHY-1412S)
- Public MQTT Broker: [broker.hivemq.com](https://www.hivemq.com/public-mqtt-broker/)
- MQTT Dashboard (Open-source IoT dashboard)

---

## 🖼️ Hardware Setup

![Hardware Setup](./MQTT-CKT.jpeg)

Sensor pin connected to **GPIO 4** on the Raspberry Pi.

---

## 🧪 Sample Output (from Raspberry Pi shell)

```text
Sensor Read - Temp: 28.0°C, Humidity: 51.0%
Published: {'temp': 28.0, 'humidity': 51.0}
Dashboard Preview

Displays:

Temperature (°C)

Humidity (%)

Real-time graphs and gauge widgets

🚀 How to Run
Connect DHT11 to Raspberry Pi (GPIO 4).

Install required Python libraries:

bash
Copy
Edit
pip install paho-mqtt Adafruit_DHT
Run the Python script.

Use any MQTT dashboard to subscribe to topic pi/dht.

✅ Future Improvements
Add LCD or OLED display

Save data to Firebase or InfluxDB

Add alert system for temperature/humidity thresholds

Create mobile/web app interface

📁 License
This project is open-source and free to use for educational and prototyping purposes.

yaml
Copy
Edit

---

### ✅ What’s Next?
If you want, I can:
- Package this into a downloadable `README.md` file.
- Help you upload it to a GitHub repository with folder structure.

Would you like that?
