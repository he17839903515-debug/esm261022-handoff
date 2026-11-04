# Power candidate review V1.4 — blocked

Reviewed YANGJIE SS510 C5339843, LGE SS54 C330398, MMBT5401 C83941 and PANJIT PPJA3463 / C2992431 as comparisons. None is approved as a drop-in: original footprint, exact manufacturer pinout, transient conditions and thermal stress remain open.

The PANJIT device has 60V drain-source rating but a 20V gate-source magnitude limit, so the existing input topology can still exceed its gate limit at a 28V input. A higher-voltage PNP does not independently fix that gate stress. Diode forward voltage, leakage, reverse surge and board heating remain to be verified; a catalog listing's 850mV at 50A is questionable against its 5A rating. No physical testing or design release.
