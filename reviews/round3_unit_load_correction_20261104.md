# Round 3: RS485 unit-load correction

The earlier 32UL-as-375-ohm differential resistor model is withdrawn. RS485 unit loading is defined by bus-input current versus voltage and common-mode conditions, not by an assumed resistor across A/B. New 220/270/330/390-ohm calculations cover only explicit unloaded dual-termination scenarios; 32UL worst-case bias remains unresolved. MAX3485 open-input failsafe must not be treated as a general terminated-idle guarantee.

J6 is the separate CAN termination jumper; J13 is the connector. The 232-position BOM remains 27 candidate and 205 blocked, with fitted identities unknown. Q12 gate protection, input surge, F3 and charger thermal/load design remain open. No physical tests or release.
