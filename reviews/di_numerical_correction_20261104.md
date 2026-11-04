# DI scan numerical correction

An earlier PowerShell scan reported zero for nonzero-voltage typical values; it must not be used. Recomputed with floating-point arithmetic: at 12 V, 2.7 kohm and assumed 1.17 V drop, current is 4.011111 mA and resistor power is 43.440333 mW; at 20 V the corresponding values are 6.974074 mA and 131.321815 mW. These are illustrative, not rated operating conditions. Real part tolerance and forward voltage remain unknown.

PST-derived connectivity places F3 upstream of VIN/Q12/VOUT, with both U22 VIN and U24 VCC on VOUT. The partial main-source scenarios exclude charger and other unknown loads; actual fuse current and thermal memory remain unresolved. No physical test or release.
