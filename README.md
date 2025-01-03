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

**Components:**
| Component | Description | Quantity | Value/Type | Image |
|---|---|---|---|---|
| Wemos D1 Mini | Microcontroller | 1 | - | ![enter image description here](https://m.media-amazon.com/images/I/513RYJXAIEL.jpg) |
| Charging Hat | For battery charging | 1 | - | ![enter image description here](https://m.media-amazon.com/images/I/510PcFVFc1S._SL1100_.jpg) |
| Li-ion Battery | Power source | 1 | - | ![enter image description here](https://www.flyrobo.in/image/cache/catalog/li-ion-18650-3.7v-2200mah-battery-1c/li-ion-18650-3.7v-2200mah-battery-1c-1-1100x1100.jpg) |
| Resistor | For voltage divider | 2 | 15kΩ, 10kΩ | ![enter image description here](https://th.bing.com/th/id/R.6692158733ac249685ee06415bb39d19?rik=7%2b/YLE1XJzuetw&riu=http://wiraelectrical.com/wp-content/uploads/2020/06/10k-ohm-real-1.jpg&ehk=CtSB%2b5UFrM2lD1SP0r77N0rnre3jx1MdGHOAUoS7uA8=&risl=&pid=ImgRaw&r=0) |
| Jumper Wires | For connections | As needed | - | ![enter image description here](https://i.pinimg.com/originals/6c/bd/07/6cbd078e05e527dec22ea271cd5dd8d2.jpg) |
| Breadboard | Optional | 1 | - | ![enter image description here](https://m.media-amazon.com/images/I/41grBNrtiEL._SY445_SX342_QL70_FMwebp_.jpg) |

**Roadmap:**

- **Data Storage:**

  Implement data storage for power outage events (start time, end time, duration).

- **Web Server:**

  Develop a web server to display real-time power status and historical outage data.

- **Email Reporting:**

  Implement daily email reports with outage summaries.

- **Data Visualization:**

  Add charts and graphs to visualize outage patterns.

- **User Authentication:**

  Add user authentication to the web interface.

- **Error Handling:**

  Implement more robust error handling.

- **Power Saving:**

  Explore alternative power saving techniques.

**Software:**

- Tasmota

- MQTT broker (e.g., Mosquitto)

- (**To be Determined:** Web server and database technologies)

**Contributing:**

Contributions are welcome! Please feel free to fork this repository and submit pull requests.
