## Premier League Historical Data

Goal: collect accurate historical data for all Premiere League games since 2000-2001 season.<br>

Reason: The data will be prepared to be used to predict this season's head-to-head winners.<br>

Collected Data: The data collected will be across all teams that played in the most recent season.<br>
Please note that older teams that used to play in the premiere league will be ignored as we are not<br>
interested in any data for older teams (they don't play anymore).

## Usage

- Create a new python virtual environment
- Execute: `pip3 install -r requirements.txt`
- Run the Jupyter Notebook
- Generated CSV files will be stored under `/data` folder

<span style="color:red;"><strong>Note:</strong></span> This will take some time. Requests are being throttled; scraping various websites and tens of thousands of data points.

## Collected Data

#### Match Results

<img src="https://github.com/walidrafeii/PremiereLeagueData/blob/main/static/match_results_example.png">

#### Team Performance by Season

<img src="https://github.com/walidrafeii/PremiereLeagueData/blob/main/static/team_perf_by_season_example.png">
