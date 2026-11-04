# Supply scenario correction V0.5.2

The earlier partial-input scenario omitted D19 forward loss. The revised computation uses U22 output power V13 × I12, including the diode drop, before dividing by U22 efficiency and input voltage. U21 efficiency is swept at 70%, 80%, and 90%. The average partial input divided by the temperature-adjusted F3 hold current is a screening ratio, not a trip prediction.

The charger, MCU, GNSS, external connections and other unknown loads remain excluded; efficiencies, duty and voltages are assumptions. Pulse timing, PPTC thermal memory, real electrical performance and physical testing remain open. No design release.
