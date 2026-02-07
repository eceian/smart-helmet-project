# smart-helmet-project


✅ EXACT WORKING LOGIC (PRIORITY BASED)

IR detects head (helmet worn)
→ Relay ON → Motor starts

While motor is running, if alcohol is detected
→ Relay OFF immediately (motor stops)
→ Buzzer ON

Even if IR still detects head,
→ Alcohol = HIGH priority → motor stays OFF

Motor ON again only when:

Alcohol is NOT detected

Helmet is worn

🔁 LOGIC PRIORITY (REMEMBER THIS)

Alcohol sensor > IR sensor

🔌 ARDUINO NANO CONNECTIONS

(Using MQ-3 D0 pin)

IR Sensor

VCC → 5V

GND → GND

OUT → D2

MQ-3 Alcohol Sensor

VCC → 5V

GND → GND

D0 → D3

Relay

IN → D4

VCC → 5V

GND → GND

Buzzer

→ D5

− → GND
