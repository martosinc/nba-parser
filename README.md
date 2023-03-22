# NBA Parser

A Python parser for scraping NBA data from basketball-reference.com.

## Installation

Just clone this repository. No further installation needed.

`git clone https://github.com/martosinc/nba-parser`

## Usage

Run `python main.py`. Depending on what do you want to do type 1, 2 or 12: Load dates(1) or create dataset(2) or both(12).  

### Loading dates

If you want to load dates type in start and end date (`YYYY-MM-DD`).  
All loaded data is stored in `/data` folder. Each game is a folder (`/YYYY-MM-DDTM1-TM2`) stored in its appropiate season folder. Each game folder consists of 5 `.csv` files: Basic and Advanced stats of every player for each team in separate files and Factors of both teams in one file; as well as `inactive.json` file, containing inactive players for each team.