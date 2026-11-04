# Round 2 evidence audit — incomplete

All 57 previously recorded RS485/CAN pin records match the PST-derived pin inventory. J13 is the CAN connector; J6 is a separate jumper that enables the 120-ohm termination. This does not prove physical copper or fitted jumper status.

A conditional 330-ohm bias example gives approximately 214 mV at 3 V with assumed 1% resistors, two 120-ohm terminations and 32 simplified 12k differential loads. Real common-mode leakage, actual receivers, protection and surge still require evaluation; it is not an approved ECO.

The local 232-position BOM remains 27 candidate and 205 blocked; 18 10k catalog matches remain blocked pending net-specific stress. Input surge, Q12 gate stress, charger current and F3 thermal behavior remain unresolved. No original CAD changes, physical tests or production release.
