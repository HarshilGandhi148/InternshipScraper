# Internship Scraper

An Java program that scrapes intership listings from https://github.com/SimplifyJobs/Summer2027-Internships and notifies a user whenever a new internship drops

## The Problem
Recently, as recruiting season has picked up, it has become harder and harder to keep track of what internships come out everyday and when they do. As applications are all rolling, applying early is key, but there is no way to notify one of when these internships are released.

## Goal
Build a Java program that periodically pull internship listings from this GitHub repo: https://github.com/SimplifyJobs/Summer2027-Internships and filters them based on my own keywords. Whenever a new relevant listing drops, the progam will send a push notification of its details.

## MVP Scope
- Fetch the listings JSON from the SimplifyJobs repo and keep only active, visible listings
- Filter by keywords
- Send out a push notification for new matches
- Run automatically on a schedule


## Tech Stack

- **Language:** Java
- **Libraries and External Tools:** Gson, java.net.http.HttpClient, ntfy.sh, curl (for testing), cron (schedule tasks)
- **Data storage:** JSON and text files

## Roadmap

- Run using GitHub Actions so it works even when computer is off
- Extra filters such as location, graduation data restrictions, and sponsorship needed
- Merge multiple listings in one notification


## Author

Harshil Gandhi, https://github.com/HarshilGandhi148