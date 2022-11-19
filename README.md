# National Weather Service Hazards and Warnings

[![Scrape all NWS hazards and warnings](https://github.com/jeremiak/nws-hazards-warnings/actions/workflows/scrape.yml/badge.svg)](https://github.com/jeremiak/nws-hazards-warnings/actions/workflows/scrape.yml)

_Source: [NOAA](https://www.wrh.noaa.gov/map/)_

`git-scrapes` the National Weather Service hazard and warning notices into a JSON file.

Deploys [to a datasette instance](https://nws-all-hazards-warnings.fly.dev/all-hazards-warnings) when data changes.
