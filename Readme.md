# Arduino MOSFET Driver

## Übersicht
Low-Side MOSFET Treiberplatine für Heizung bis 12 V / 5 A.  
Gate-Treiber: MCP1402 SOIC-8  
MOSFET: IRF3806 D2PAK  
PWM-Steuerung direkt vom Arduino (5 V).

## Bauteile
- MCP1402 SOIC-8 (Gate-Treiber)
- IRF3806 D2PAK (MOSFET)
- Rg = 47 Ω (Gate)
- Rpd = 10 kΩ (Pulldown Gate)
- Cdec = 100 nF (Bypass am Treiber)
- D1 = 1N5822 Schottky (Freilaufdiode)
- Last: 12 V Heizung, bis 5 A

## Anschlüsse
- 3-poliger Header für PWM-Eingang vom Arduino
- Schraubklemmen für +12 V / GND / Last

## Hinweise
- PWM-Frequenz bis 20 kHz
- Gemeinsame Masse zwischen Arduino und Treiber/Last
- Thermal Pads für D2PAK MOSFET großzügig dimensionieren

