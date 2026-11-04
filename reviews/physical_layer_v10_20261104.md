# RS485/CAN physical layer audit V1.0 — open

PST-derived connectivity traces the RS485 transceiver through per-line F1/F2 to J12, with a fixed 120-ohm local termination and 10k pull-up/pull-down. Under ideal 3.3V conditions the 10k/120/10k bias is approximately 19.68mV differential, insufficient by itself to establish a 200mV noise margin. Fitted values, surge coordination and alternate-transceiver pin compatibility remain unverified.

CAN is routed through SP00S12 to J13, with J6 enabling the 120-ohm termination. The PE and circuit-ground networks are connected through nominal 1Mohm and 1nF components; the transceiver circuit is not galvanically isolated. Jumper population, protective-device response, PCB continuity, EMC and firmware behavior require validation. No physical tests or parity signoff.
