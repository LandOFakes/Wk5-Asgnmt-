# IS 362 Week 5: Airports, Geography & Wind

**Author: Precious Brown**

A Python/pandas notebook investigating airport locations and NYC area wind observations, with purple charts and documented research.

## Files

- `PBrownWeek5.ipynb`: completed notebook with executed outputs, Markdown explanations, research, and purple charts.
- `PBrownWeek5.md`: a cell-by-cell copy of the notebook text and code. Markdown cells belong in Markdown cells, not Code cells.
- `data/airports.csv` and `data/weather.csv`: unchanged source downloads from the assigned nycflights13 repository, retrieved October 4, 2026.
- `requirements.txt`: dependencies.

## Run locally

From this folder:

```bash
python -m pip install -r requirements.txt
python -m jupyter notebook
```

Open the notebook, select the Python 3 kernel, and run all cells. The data loader uses included local CSV files and falls back to the assigned GitHub raw URLs.

## Run in Google Colab

Open the notebook in Colab and run all cells. If the data folder is not uploaded, the notebook downloads the original CSV files using its fallback URLs. An internet connection is then required.

## Findings

- Northernmost reviewed airport: BRW in Alaska.
- Easternmost under a U.S. west-to-east convention: EPM in Maine. Under greatest signed longitude, SYA in Alaska is the alternative answer.
- Windiest NYC area airport on February 12, 2013: LGA, after excluding the invalid Newark observation.

The notebook explains why EEN, MYF, and DVT are excluded from geographic rankings, why SYA is retained, and why Newark's 1,048.36058 mph wind-speed value is marked missing. The raw files are never overwritten.

## Upload to GitHub and submit

1. Create a public repository named `Wk5-Asgnmt-` in your GitHub account.
2. Extract the project ZIP on your computer.
3. Upload the contents of this project folder, keeping the `data` folder intact. Do not upload only the ZIP.
4. Commit the files.
5. Open `PBrownWeek5.ipynb` on GitHub and check that its text and outputs render.
6. Copy that notebook page's URL and submit it to your professor.

Review the assumptions and explanations before submitting so you can explain the cleaning decisions. GitHub may omit the purple HTML title styling; the chart colors are embedded in the notebook outputs.
