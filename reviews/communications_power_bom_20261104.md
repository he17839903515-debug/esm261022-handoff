# Communications, BOM and OVLO progress

The PST-derived physical layer audit now includes 57 pin records and eight open issues. Ideal RS485 10k/120/10k bias at 3.3 V is about 19.68 mV; fitted values, alternate pin compatibility and connector surge behavior remain open. CAN and RS485 functions remain in scope.

The local 232-position BOM v1.5 adds 18 provisional 10k catalog matches, still blocked pending circuit stress and footprint review; counts remain 27 candidates and 205 blocked.

TI TPS26600 OVP reference spread alone makes an ideal divider with a 27.5 V maximum rising threshold have a minimum about 26.265 V; guaranteeing no cutoff below 28 V entails a maximum about 29.316 V. Leakage, resistor tolerance and delay worsen the design problem. This is not a final circuit or a test. Charging, battery and all interfaces remain in scope.
