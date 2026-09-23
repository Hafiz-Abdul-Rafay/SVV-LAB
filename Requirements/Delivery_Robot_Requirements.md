# Delivery Robot – Requirements

| Req. ID | Requirement |
|---|---|
| R1 | System shall remain in IDLE state until a delivery request is received |
| R2 | System shall transition to NAVIGATING state upon receiving a delivery request |
| R3 | System shall continuously monitor for obstacles while in NAVIGATING state |
| R4 | System shall transition to AVOIDING_OBSTACLE state when an obstacle is detected |
| R5 | System shall resume NAVIGATING state once the obstacle is successfully avoided |
| R6 | System shall transition to DELIVERING state only after reaching the destination |
| R7 | System shall transition to RETURNING state after successful package delivery |
| R8 | System shall monitor battery level continuously during NAVIGATING and RETURNING |
| R9 | System shall transition to RETURNING state if battery becomes critically low, regardless of current delivery progress |
| R10 | System shall transition to IDLE state only after reaching the warehouse |
