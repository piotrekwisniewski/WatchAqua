# WatchAqua
A project aimed at gaining an overview of how humanity uses the world's water resources.


## Project preparing

To run WatchAqua project it is needed to download full dataset from United Nations AQUASTAT database and save it as a CSV file named AQUASTAT_2025.csv. File should be saved in diretory: /data/1_raw/ 

Link for bulk download (English version):
https://storage.googleapis.com/810c63d8-3fde-4ecd-9882-14d62e3058be/static/sites/aquastat/bulk/bulk_eng(in).csv

OR

file could be chosen manually from the UN Aquastat system:
[https://www.fao.org/aquastat/en/](https://data.apps.fao.org/aquastat/?lang=en)

```text
## Project Structure:

WatchAqua/
└── data/
    ├── 1_raw/           # Raw data (here AQUASTAT_2025.csv should be saved in).
    └── 2_processed/     # Data processed after ETL
```
