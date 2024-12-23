# Power Outage Monitor

**Current Status:**

- **Power Monitoring:**
  - Tasmota device is configured to monitor power status using a GPIO pin.
  - Power status (ON/OFF) is published to an MQTT topic.
- **Data Collection:**
  - MQTT subscriber is receiving power status updates.
  - (**In Progress:** Data collection and storage implementation)

![](./images/wemos_diagram.png)

**Voltage Divider:**

![Voltage Divider Using resisters](./images/voltage_divider.png)

**Roadmap:**

- **Data Storage:**
  - Implement data storage for power outage events (start time, end time, duration).
- **Web Server:**
  - Develop a web server to display real-time power status and historical outage data.
- **Email Reporting:**
  - Implement daily email reports with outage summaries.
- **Data Visualization:**
  - Add charts and graphs to visualize outage patterns.
- **User Authentication:**
  - Add user authentication to the web interface.
- **Error Handling:**
  - Implement more robust error handling.
- **Power Saving:**
  - Explore alternative power saving techniques.

**Hardware:**

- ESP8266/ESP32 (Tasmota-flashed)
- Charging hat
- Li-ion battery
- Resistors (for voltage divider)
- Breadboard (optional)
- Jumper wires

**Software:**

- Tasmota
- MQTT broker (e.g., Mosquitto)
- (**To be Determined:** Web server and database technologies)

**Contributing:**

Contributions are welcome! Please feel free to fork this repository and submit pull requests.
