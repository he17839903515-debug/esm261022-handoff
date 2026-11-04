# Main power review V0.2: partial

PST-derived pin connections indicate Q12 gate is pulled toward ground via R55/R56 while Q14 is off. If the fitted MOSFET is AOS AO3401 and the source reaches 20–28 V, the implied gate-source voltage can exceed its ±12 V absolute maximum. Actual population, dynamic behavior and native symbol mapping remain unverified. This is a risk calculation, not a measured failure.

The F3 library field matches the manufacturer part name Fuzetec FSMD010-1206-R; its 23°C hold/trip currents are 0.10/0.25 A, with 60 V rating. The field does not prove fitted identity. The complete load, device selection, diode thermal design and protection coordination remain open; no production release.
