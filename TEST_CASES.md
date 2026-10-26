# DriveSense Test Cases

| ID | Test | Expected Result |
|---|---|---|
| TC01 | Load valid CSV data | Data loads successfully |
| TC02 | Missing required column | Validation error is reported |
| TC03 | Empty CSV file | Application handles empty input |
| TC04 | Eye-closure feature changes | Estimator follows documented logic |
| TC05 | Head movement changes | Feature is processed correctly |
| TC06 | PPG sensor disconnects | Missing sensor is reported |
| TC07 | IMU sensor disconnects | Missing sensor is reported |
| TC08 | Poor signal quality | Invalid input is flagged |
| TC09 | Invalid timestamps | Affected data is rejected or corrected |
| TC10 | Camera unavailable | Clear error is displayed |
| TC11 | Alert condition is reached | Configured alert logic is applied |
| TC12 | SOS disabled | No external SOS action is triggered |

## Test Execution Record
Record the test date, software version, hardware, input dataset, actual result, and any defects.

**Important:** These are planned tests. Record Pass only after running each test and verifying the result. Use simulated data or stationary testing, never public-road driving tests with an unvalidated prototype.
