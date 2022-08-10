# Analytics Pipeline

This repo contains the code for creating a data pipeline to calculate metrics for a fake webserver:

* `log_generator.py` -- generates fake webserver logs.
* `store_logs.py` -- parses the logs and stores them in a SQLite database.
* `count_visitors.py` -- pulls from the database to count visitors to the site per day.

# Installation

To get this repo running:

* Clone this repo with `git clone https://github.com/abreham-g/Analytics-Pipeline.git`
* Get into the folder with `cd analytics-pipeline`
* Install the requirements with `pip install -r requirements.txt`

# Usage

* Execute the three scripts mentioned above, in order.

You should see output from `count_visitors.py`.

