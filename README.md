Job-Tracker: Destatis, Bundesbank, KfW, Land Hessen, Deutsche Börse

Durchsucht automatisiert die Stellenangebote von:

  - Statistisches Bundesamt (Destatis)  -> destatis.de (INTERAMT-Widget, JS)
  - Deutsche Bundesbank                 -> bundesbank.de/de/karriere/jobboerse (statisches HTML)
  - KfW Bankengruppe                    -> jobs.kfw.de (JS-Portal)
  - Land Hessen                         -> stellensuche.hessen.de (SAP-Fiori-SPA, JS)
  - Deutsche Börse                      -> careers.deutsche-boerse.com (statisches HTML)

Filters by keywords, excludes internships/part-time student jobs, etc., keeps track of
jobs already viewed (seen_jobs.json), and displays only NEW
results each time the script runs. The results are also saved in full as a CSV file (including location).

Install:
    pip install requests beautifulsoup4 --break-system-packages
    pip install playwright --break-system-packages
    playwright install chromium         # einmalig, lädt den Headless-Browser
