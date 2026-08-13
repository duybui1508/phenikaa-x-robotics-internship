# Module 4 — Industrial control, sensing and safety

## Scope

- Configured an MD400 driver and controlled a BLDC motor through MDAS over RS-485, including speed, direction and status monitoring.
- Worked with AMR sensing devices: magnetic line sensor, WT901 IMU and RFID reader.
- Configured SICK TiM320 detection fields and observed digital outputs for layered warning/stop zones.
- Studied and tested bumper, warning-light, emergency-stop, reset and electromagnetic-brake behavior.
- Practiced a warehouse pick-and-return sequence using Delta DVP12SE11T PLC, WPLSoft and HMI.

## Artifacts to add

```text
bldc/
  mdas_velocity_plot.png
sensors/
  magnetic_line_response.png
  imu_plot.png
  rfid_readout.png
safety/
  tim320_fields_redacted.png
plc_hmi/
  sequence_flowchart.png
media/
  industrial_system_demo.mp4
```

## Results to report

- BLDC commanded and measured speed response.
- IMU output rate and calibration behavior.
- RFID tag read result and repeatability.
- TiM320 response for each configured field.
- Pick-and-return cycle time and success rate.

Keep device credentials, internal addresses and original company PLC/HMI programs out of the public repository.

