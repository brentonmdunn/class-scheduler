The URLs from each department page are scraped using `url_scraper.py` and are saved in a 1 column `.csv` called `courses_<dept>.csv`. `courses_<dept>.csv` is currently stored in `scrapers/` but eventually will be moved ot `csv/`. `course_scraper.py` is then used to go through each URL listed in `courses_<dept>.csv` and writes each section to individual json files stored in `scrapers/json/`.

Do not have new line at end of `courses.csv`

moving files: https://www.learndatasci.com/solutions/python-move-file/

dump vs dumps: https://www.geeksforgeeks.org/python-difference-between-json-dump-and-json-dumps/

Branch naming rules: `<Feature> or <Bug>/<username>/<small description>`
