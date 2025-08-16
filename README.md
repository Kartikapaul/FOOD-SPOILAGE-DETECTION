I have designed An IoT-based project that detects food spoilage using gas sensors (MQ3) and environmental sensors (DHT11). The system monitors temperature, humidity, and gas levels to identify food freshness and sends real-time data to ThingSpeak for visualization. It also provides alerts through an LCD display and can be extended to mobile apps for user-friendly monitoring.
Features:
-Temperature & Humidity Monitoring using DHT11 sensor
-Gas Detection using MQ3 sensor to detect spoilage gases
-LCD Display Output for real-time values
-ThingSpeak IoT Integration for cloud-based data logging and visualization
-Spoilage Alerts when sensor values exceed safe thresholds
-Low-cost and scalable system for kitchens, storage, and supply chains
Components Used:
-Node MCU ESP38266
-MQ3 Sensor 
-DHT 11
-LCD Display
-Resistors
Software Used:
-Thingsapeak
Working Principle:
-Sensors (MQ3 & DHT11) measure gas levels, temperature, and humidity.
-The data is processed by ESP board.
-Real-time results are displayed on the LCD screen.
-Sensor readings are uploaded to ThingSpeak cloud for visualization.
-If values exceed safe thresholds, the system raises a spoilage alert
