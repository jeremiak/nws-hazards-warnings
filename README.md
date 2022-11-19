# National Weather Service Hazards and Warnings

`git-scrapes` the [National Weather Service](https://www.wrh.noaa.gov/map/) hazard and warning notices into a JSON file.

Deploys [to a datasette instance](https://nws-all-hazards-warnings.fly.dev/all-hazards-warnings) when data changes.

[![Scrape all NWS hazards and warnings](https://github.com/jeremiak/nws-hazards-warnings/actions/workflows/scrape.yml/badge.svg)](https://github.com/jeremiak/nws-hazards-warnings/actions/workflows/scrape.yml)

[![Deploy with Datasette](https://github.com/jeremiak/nws-hazards-warnings/actions/workflows/deploy.yml/badge.svg)](https://github.com/jeremiak/nws-hazards-warnings/actions/workflows/deploy.yml)