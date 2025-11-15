this would be the file stucture and what to be in it ig lol

IDS-Email-a3/
│
├── main.py
├── README.md
├── Report.pdf
│
├── data/
│   ├── Events.txt
│   ├── Stats.txt
│   ├── baseline_stats.txt     # output from analysis
│   └── logs/
│       ├── day1.log
│       ├── day2.log
│       └── ...
│
└── src/
    ├── event_parser.py        # read Events.txt + Stats.txt, validate
    ├── activity_engine.py     # generate simulated events + logging
    ├── analysis_engine.py     # compute means, SD, baseline
    └── alert_engine.py        # anomaly detection + thresholds
