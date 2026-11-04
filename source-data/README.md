# Source Data

Monthly expense records in CSV format.

| File | Period |
|------|--------|
| january.csv | January |
| february.csv | February |
| march.csv | March |
| april.csv | April (added in Version 2) |

## How the auto-update works
The CSV files are combined in Excel using Power Query (Get Data > From Folder). When a new month's CSV is added to the folder, clicking Refresh All loads the new records, and the Pivot Tables, charts, KPI cards and slicers update automatically.

All files use the same column headers in the same order, which is what allows Power Query to combine them.

Data is simulated for practice.
