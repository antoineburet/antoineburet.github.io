---
layout: default
---

Welcome! I'm a final-year engineering student at IMT Nord Europe, specializing in Data Science and Cybersecurity. I'm passionate about building tools that help defend and secure systems.

---

## Projects

### [SQL Injection Prevention Demo](https://github.com/antoineburet/sql-injection-prevention-demo)

`Node.js | Express | MySQL | Security`

A web application demonstrating a classic SQL Injection (SQLi) vulnerability and, more importantly, how to prevent it.

* Compares a **vulnerable login** route (using string concatenation) with a **secure login** route (using parameterized queries).
* Demonstrates **two major flaws** simultaneously: SQL Injection and storing passwords in plain text (`password_clear`).
* The secure route properly uses **`bcrypt`** for password hashing and comparison, making it safe.

*This project is a hands-on lab to illustrate the critical difference between insecure and secure authentication code.*

---

### [CISA KEV Analyzer](https://github.com/antoineburet/cisa-kev-analyzer)

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

-----

## Cybersecurity Learning

I started my hands-on cybersecurity journey on [TryHackMe](https://tryhackme.com/p/Nyota0) on Monday, November 10, 2025. Here is my live profile badge:

<iframe src="https://tryhackme.com/api/v2/badges/public-profile?userPublicId=1743418"
style="border:none; width: 350px; height: 180px;">
</iframe>

-----

## Connect

  \* [LinkedIn](https://linkedin.com/in/antoine-buret)
  \* [GitHub](https://github.com/antoineburet)
