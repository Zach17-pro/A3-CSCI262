## Project Structure

```
IDS-Email-A3/
├── main.py                 # Main application entry point
├── README.md              # Project documentation
├── Report.pdf             # Analysis report
├── data/                  # Data directory
│   ├── Events.txt         # Event data input
│   ├── Stats.txt          # Statistics data input  
│   ├── baseline_stats.txt # Analysis output
│   └── logs/              # Application logs
│       ├── day1.log
│       ├── day2.log
│       └── ...
└── src/                   # Source code
    ├── event_parser.py    # Parse and validate events/stats
    ├── activity_engine.py # Generate simulated events
    ├── analysis_engine.py # Compute means, SD, baseline
    └── alert_engine.py    # Anomaly detection
```
