# State Transition Table

| Current State | Event | Next State |
|---|---|---|
| IDLE | Delivery Request Received | NAVIGATING |
| NAVIGATING | Obstacle Detected | AVOIDING_OBSTACLE |
| AVOIDING_OBSTACLE | Obstacle Avoided | NAVIGATING |
| NAVIGATING | Destination Reached | DELIVERING |
| NAVIGATING | Critical Battery | RETURNING |
| AVOIDING_OBSTACLE | Critical Battery | RETURNING |
| DELIVERING | Delivery Successful | RETURNING |
| RETURNING | Warehouse Reached | IDLE |
