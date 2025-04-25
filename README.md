# Energy-Meter
Energy metering PCB based on RN7302 chip

## English:

The PCB is designed to measure:
	- **Active, reactive, and apparent power, as well as power factor.
	- **Current and voltage (RMS).
	- **Frequency.
	- **Harmonics.
	- **Other parameters (see the attached datasheet for more information).
	- **Additionally, it has a relay output to control a contactor.

The measurement chip is the RN7302, which is connected to an ESP32 microcontroller via the SPI interface.

Connections:
• P1, P2, P3, P4 correspond to L1, L2, L3, and N, respectively.

Specifications:
• Maximum measurement current (Imax): 5 A
• Maximum measurement voltage (Umax): 300 V



## Deutsch:

Die Leiterplatte (PCB) ist dafür ausgelegt, folgende Werte zu messen:
	- **Wirkleistung, Blindleistung und Scheinleistung sowie den Leistungsfaktor.
	- **Strom und Spannung (Effektivwert, RMS).
	- **Frequenz.
	- **Oberschwingungen.
	- **Weitere Parameter (siehe das beigefügte Datenblatt für mehr Informationen).
	- **Zusätzlich verfügt sie über einen Relaisausgang zur Steuerung eines Schützes.

Der Messchip ist der RN7302, der über die SPI-Schnittstelle mit einem ESP32-Mikrocontroller verbunden ist.

Anschlüsse:
• P1, P2, P3, P4 entsprechen L1, L2, L3 und N.

Spezifikationen:
• Maximale Messstromstärke (Imax): 5 A
• Maximale Messspannung (Umax): 300 V


