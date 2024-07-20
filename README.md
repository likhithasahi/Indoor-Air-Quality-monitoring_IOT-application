# Indoor-Air-Quality-monitoring_IOT-application
**INTRODUCTION**
Air Quality Sensor
It assesses various parameters andpollutants present in the air to provide valuable insights into the overall airquality. These sensors play a crucia role in maintaining a healthy and safeindoor or outdoor environment by detecting harmful pollutants andgases.
DHT11 Sensor
A humidity sensor, also called ahygrometer, is a device used tomeasure the moisture content or humidity level in the air and temperature.
**Components Used**
NodeMCU: Facilitates monitoring soil moisture and water levelscontrolling the motor, and sending data to the cloud through its integrated Wi-Fi capabilities
Breadboard: Provides a platform for temporary connections, aiding in prototyping the circuit.
Jumper Wires: Enable easy connections between components, ensuring seamless signal transmission
**Connections**
FOR DHT11:
  GND to GND
  DATA of DHT11 to D4 of NodeMCU
  VCC to Vin
FOR MQ 135:
  A0 to A0
  GND to GND
  VCC to 3.3V
**Protocols Used**
HTTP (Hypertext Transfer Protocol) - For web pageaccessing and pushing data to Thingspeak.
Wi-Fi (Wireless Fidelity) - Connecting NodeMCU to the Internet.
MQTT (Message Queuing Telemetry Transport) - For thedata transfer for Thingspeak to IFTTT. MQTT is used for data analysis in Thingspeak.
