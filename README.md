```markdown
# Pi-EnvMonitor
Raspberry Pi Environment Monitor

This project uses Raspberry Pi as the main controller with a DHT11 digital temperature and humidity sensor to periodically collect indoor temperature and relative humidity.
The collected sensor data will be uploaded to the backend server and stored persistently in a database. A web visualization page is built, which can be accessed from the public network to view real-time temperature and humidity data.

## ✨ Features
- Periodic sampling of temperature and humidity
- Persistent data storage, support for historical data query
- Web dashboard with data curve visualization
- Public network access, check environment data remotely
- Lightweight architecture, great for embedded IoT learning

## 🛠️ Hardware List
- Raspberry Pi
- DHT11 Temperature & Humidity Sensor
- Jumper wires

## ⚙️ Requirements
- Python 3
- DHT sensor library
- Flask (web backend)
- SQLite / MySQL database

## 🚀 Quick Start
1. Wire the DHT11 sensor to the GPIO pins of Raspberry Pi.
2. Clone this repository to your Raspberry Pi.
```bash
git clone https://github.com/Y-del-bot/Pi-EnvMonitor.git
cd Pi-EnvMonitor

