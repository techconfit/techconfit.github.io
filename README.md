# Italy Tech Conferences 🇮🇹

A community-curated list of Italian tech conferences.
Inspired by:

* 


# Adding a conference

Send a pull-request which adds a file to the `_conferences/` directory
with a new file representing the conference. The file should be named
with the conference name, the year, and with an `.md` extension (for
example, `devfest-pisa-2020.md`).

The contents of the file should use the following template:
```
---
name: "GDG DevFest"
website: https://devfest.gdgpisa.it/
location: Pisa, Italy

date_start: 2020-04-18
date_end:   2020-04-19

cfp_start: 2020-01-15
cfp_end:   2020-02-17
cfp_site:  https://sessionize.com/devfest-pisa-2020
---
```

*Note: Do not include the location of the conference in the name. The above conference is often referred to as "GDG DevFest", but we will always render the location with the name so it is redundant.*

Running locally
---------------

```
bundle install
bundle exec jekyll serve
```

Once running the site can be opened at http://localhost:4000.


License
-------

All content is [CC0][1].


 [1]: https://creativecommons.org/publicdomain/zero/1.0/
