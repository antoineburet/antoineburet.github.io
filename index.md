---
layout: default
---

Welcome! I'm a final-year engineering student at IMT Nord Europe, specializing in Data Science and Cybersecurity. I'm passionate about building tools that help defend and secure systems.

---

## Projects

### [CISA KEV Analyzer](https://github.com/antoineburet/CISA-KEV-Analyzer)

`Python | API | Threat Intelligence | CLI`

A command-line tool to query, analyze, and enrich the CISA Known Exploited Vulnerabilities (KEV) catalog.

* Fetches data from the CISA KEV catalog and provides smart local caching.
* Enriches findings with CVSS scores and severity by querying the NVD 2.0 API.
* Filters results by date, vendor, or number of entries.
* Exports reports to the console, JSON, or CSV.

*This tool was originally developed as a technical challenge for a SOC/Blue Team internship interview.*

#### Example Usage

```bash
# Get the last 5 vulns from the last 30 days (default)
$ python3 kev_analyzer.py

# Get the top 2 vulns from the last 60 days, with CVSS scores
$ python3 kev_analyzer.py -n 2 -d 60 --enrich

# Search for "Microsoft" and export to JSON
$ python3 kev_analyzer.py -n 10 -d 180 -s "Microsoft" -f json -o microsoft_report.json
````

## Connect

  * [LinkedIn](https://linkedin.com/in/antoine-buret)
  * [GitHub](https://github.com/antoineburet)
