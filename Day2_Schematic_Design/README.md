# Day 2: Schematic Design

## Work Done:
- Started schematic design block-by-block
  1. **Sensor Block**: SHT20 sensor connected with pull-up resistors and decoupling capacitors
  2. **Communication Block**: RS485 transceiver (MAX485) with A/B lines and connectors
- Placed all components in the schematic
- Assigned **net labels** to all important connections:
  - VCC → power supply
  - GND → ground
  - SDA → I²C data line
  - SCL → I²C clock line
  - A / B → RS485 differential communication lines
- Reviewed initial connections to ensure correctness
- Confirmed component selection (resistors, capacitors, connectors)

## Components Used:
- SHT20 Temperature & Humidity Sensor
- RS485 Transceiver (e.g., MAX485)
- Resistors (pull-ups for I²C, general connections)
- Capacitors (decoupling/bypass)
- Connectors/Terminals (for power input and RS485 interface)

## Notes:
- Ensured correct placement of components within schematic blocks
- Each net label clearly identifies signal connections for later PCB routing
- This schematic forms the basis for PCB layout
