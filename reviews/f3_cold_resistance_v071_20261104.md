# F3 cold resistance sensitivity V0.7.1

For the FSMD010-1206-R comparison part, 1.6 ohm is the specified minimum resistance and 15 ohm is post-trip R1max, not the maximum normal cold resistance. Actual installed part and cold resistance are unknown. At a hypothetical 0.65625 A, 1.6 ohm gives 1.05 V drop and 0.689 W; at 1 A it gives 1.6 V and 1.6 W. These are conditional minimum-resistance calculations, not evidence the PPTC remains cold or survives.

The earlier ideal VOUT=VIN charger sensitivity omitted that drop and heating. A 0.1 A hold rating does not support sustained approximately 1 A charger-path operation; actual PPTC dynamics, load and thermal coordination remain open. No physical test or signoff.
