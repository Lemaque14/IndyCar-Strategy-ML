# IndyCar Strategy ML Project Coming Soon...



\###Potential Structure:



IndyCar-Strategy-ML/

├── README.md

├── data/

│   ├── raw/              # scraped PDFs and source files

│   ├── processed/        # cleaned CSVs per table

│   └── existing/         # dataset lives here

├── scrapers/

│   ├── race\_results.py   # race metadata + caution summary

│   ├── pit\_stops.py      # pit stop summary extraction

│   ├── lap\_chart.py      # lap-by-lap position matrix

│   ├── section\_data.py   # individual lap times

│   ├── qualifying.py     # qual times/speeds/rounds

│   └── practice.py       # practice session results

├── features/

│   ├── strategy.py       # stint length, caution pits, strategy type

│   ├── position.py       # lap1 gains, volatility, laps led

│   └── pace.py           # degradation, consistency, relative pace

├── models/

│   ├── finish\_predictor/  # enhanced model

│   ├── strategy\_classifier/

│   ├── caution\_impact/

│   └── stint\_model/

├── notebooks/            # EDA and prototyping

└── config/

&#x20;   └── tracks.yaml       # track metadata (length, type, etc.)

