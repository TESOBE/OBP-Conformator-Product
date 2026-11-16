# OBP-Conformator-Product

The public website for Conformator, the conformance testing tool built on the Open Bank Project. Conformator itself is in [OBP-Frontend](https://github.com/OpenBankProject/OBP-Frontend), in `apps/conformator` and `apps/conformator-runner`.

The site is plain HTML and CSS, with no build step. Everything published is in `docs/`, so GitHub Pages can serve that folder directly.

## Seeing it locally

Open `docs/index.html` in a browser, or serve the folder:

```sh
cd docs
python3 -m http.server 8000
```

Then go to http://localhost:8000.

## Publishing

In the repository's settings on GitHub, under Pages, choose to deploy from the main branch and the `docs` folder. To use a domain of our own, add a `docs/CNAME` file containing it, as the Cohort and Senti sites do.

## What is here

- `docs/index.html`: the page.
- `docs/style.css`: the styles, shared in design with the Cohort site, in Conformator's indigo and green. Light and dark modes follow the visitor's settings.
- `docs/img/`: the TESOBE logo, the Open Bank Project mark, and `mark.svg`, a first version of Conformator's mark: a C with a gap, and the piece that fits it exactly.

## Writing for the site

Write in plain UK English, as in OBP-Frontend's README ("Writing documentation"): short sentences, everyday words, and the active voice. Describe what Conformator does for each kind of user. Do not name individual customers or tenders.

## Licence

AGPL-3.0, as the rest of the Open Bank Project. See [LICENSE](LICENSE).
