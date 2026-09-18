# Soil-Moisture-Monitoring-System
Soil Moisture Monitoring System 🌱 
Built and simulated an automatic soil moisture monitor on Arduino Uno.

How it works:

→ Soil moisture sensor feeds an analog reading into A0

→ Arduino compares it against a dryness threshold

→ If the soil is dry, the motor turns ON and waters the plant

→ Once moisture crosses the threshold, the motor cuts OFF automatically

→ A 128x64 I2C OLED shows live value, soil state, motor status and whether moisture is rising or falling

The trend indicator was the fun part — instead of just showing a number, it compares consecutive readings so you can see the soil actually responding to watering in real time.

Designed and tested in Proteus before touching hardware. Catching wiring and logic mistakes in simulation saved me a lot of time.

Next step: moving it to real hardware with a relay-driven pump.

#EmbeddedSystems #Arduino #IoT #Proteus #ECE
