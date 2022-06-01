# Contribute to this repository

## How to choose the event 🧐

This repo is create to be a community-curated list of Italian tech conferences. So, before adding a new event, please be sure:

- make sure it is a tech conference and it is not already listed.

- make sure that is a conference (not a meetup, hackaton, etc.)

- make sure that the event is happenign in Italy (either in Italian or in a foreing language).

## Prepare the contribution ✍️

Fork this project to your github account and create the file inside the `_conferences/` directory.

The file create should be named with the conference name, the year, and with an `.md` extension (for example, `devfest-pisa-2020.md`).

## File format 📄

The contents of the file should use the following template:

`name`: the name of the conference, avoid to add the location of the event in the name, the location will be displayed near the name of the conference.

`website`: the website of the conference, avoid to link directly the event organization (Eventbrite, Meetup, etc...) instead try to find the official event website, to allow users to find more information about the event.

`location`: the location of the conference (`<city>, <country>`, `Online` or both)

`online`: if the conference is online (`true` or `false`)

`date_start`: the start date of the conference (`YYYY-MM-DD`)

`date_end`: the end date of the conference (`YYYY-MM-DD`)

`cfp_start`: the start date of the call for papers (`YYYY-MM-DD`)

`cfp_end`: the end date of the call for papers (`YYYY-MM-DD`)

`cfp_site`: the website of the call for papers (`https://sessionize.com/devfest-pisa-2020`)

Example:

```markdown
---
name: "GDG DevFest"
website: https://devfest.gdgpisa.it/
location: Pisa, Italy
online: true

date_start: 2020-04-18
date_end:   2020-04-19

cfp_start: 2020-01-15
cfp_end:   2020-02-17
cfp_site:  https://sessionize.com/devfest-pisa-2020
---
```

## Create a pull request 📌

Before push, please verify that the file is correctly formatted ([try to run the project](/README.md#running-locally) in you local machine).

There are not convention for the commit message, but it is recommended to use the following format: `"Add <conference name> <year>"`.

Then commit the changes, push the code and create a pull request.
