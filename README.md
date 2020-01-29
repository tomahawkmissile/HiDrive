# HiDrive
High power smart DC/DC switching converter

**Note: this is a conceptual project in its alpha stages.**

Planned features:
- Wide VIN and bidirectional (4.5-80VDC on HV, 4.5-65VDC on LV)
- Buck-boost topology with configurable output voltage (80V MAX on HV, 65V MAX on LV)
- Max current (50A)
- Full telemetry of voltages, currents, temperatures, and overall system health
- UVLO/OVLO
- Reverse polarity protection and indicator
- I2C external control (I2C mux required for multiple HiDrive's due to address conflicts)
