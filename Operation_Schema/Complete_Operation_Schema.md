# Task 2: Complete Operation Schema

| ID | Operation | Pre-Condition | Input | Post-Condition |
|---|---|---|---|---|
| OP01 | Perform Self-Check | Chamber is powered on | Sensor and control-device status | Essential devices are verified. |
| OP02 | Load Environmental Profile | Artifact information is recorded | Environmental limits | Required environmental profile is loaded. |
| OP03 | Monitor Environmental Conditions | Artifact is inside and sensors are working | Temperature and humidity readings | Environmental conditions are monitored. |
| OP04 | Check Door Status | Chamber is operational | Door sensor reading | Door status is determined. |
| OP05 | Correct Temperature | Temperature is outside permitted range | Current temperature and required temperature | Temperature correction is initiated. |
| OP06 | Correct Humidity | Humidity is outside permitted range | Current humidity and required humidity | Humidity correction is initiated. |
| OP07 | Verify Environmental Recovery | Correction has been initiated | Updated sensor readings | Environmental recovery is confirmed or rejected. |
| OP08 | Activate Additional Environmental Controls | Environmental condition cannot be corrected normally | Protection condition | Additional controls are activated. |
| OP09 | Reduce Light Exposure | Artifact requires protection | Light-control command | Light exposure is reduced. |
| OP10 | Generate Operator Alert | Abnormal condition occurs | Alert information | Museum operator is alerted. |
| OP11 | Detect Significant Vibration | Artifact is inside the chamber | Vibration sensor reading | Significant vibration is detected. |
| OP12 | Suspend Risk-Increasing Activities | Significant vibration is detected | Vibration event | Risk-increasing activities are suspended. |
| OP13 | Verify Vibration Stabilization | Vibration has stopped or decreased | Vibration readings and stabilization time | Vibration stabilization is confirmed or rejected. |
| OP14 | Suspend Conservation Activities | Chamber door is opened during conservation | Door-open signal | Normal conservation activities are suspended. |
| OP15 | Verify Conditions Before Resuming | Chamber door is closed again | Environmental readings and sensor status | Conditions are verified before resuming. |
| OP16 | Switch to Emergency Power | Normal power is lost | Power-loss signal | Emergency power is activated if available. |
| OP17 | Record Power Incident | Normal and emergency power are unavailable | Power-loss information | Power incident is recorded. |
| OP18 | Perform Safe Shutdown | No usable power is available | Power failure condition | System enters safe shutdown. |
| OP19 | Verify Safe Artifact Removal | Operator requests artifact removal | Chamber safety and protection status | Artifact removal is approved or rejected. |
