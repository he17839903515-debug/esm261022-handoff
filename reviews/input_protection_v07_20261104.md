# Input protection V0.7 — not signed off

The primary path supplies both the U22 regulator and CN3703 charger. Conditional scenarios combine the charging load with relay, DI, external-load and modem contributions; unknown loads and timing remain excluded. The 0.1 A hold FSMD010 comparison cannot support the continuous 1 A charging scenario. Its time-current curve and thermal memory must be evaluated rather than interpreting a hold ratio as trip time.

A 60 V eFuse, input surge clamp and coordinated downstream voltage control are a candidate architecture, not a selected design. Nominal 28 V input leaves no positive operating-voltage margin for the 28 V maximum CN3703; OVLO alone cannot guarantee both uninterrupted operation at that maximum and cutoff below it without additional design measures. Source surge, SOA, current limit, OVLO tolerance, thermal behavior and battery/port backfeed remain open. All battery and charger functions remain in scope; no physical tests.
