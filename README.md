# Monorepo

This was my first attempt at rebuilding [anchorage.org.au](https://anchorage.org.au) in my own time, with a view to also rebuilding [livinggracedianella.org.au](https://livinggracedianella.org.au) and [68waverley.org.au](68waverley.org.au) using the same setup (all belonging to the same organisation). It is the first site I built using [Astro](https://astro.build). It was not integrated with a CMS as in [the latest redesign](github.com/livinggracedianella/website-redesign) which I am currently leading.

Initially I ported my [policy doc template](https://github.com/rohannelson/livinggracedocs) into Astro (with some improvements). Then I setup the monorepo using [npm workspaces](https://docs.npmjs.com/cli/v7/using-npm/workspaces) so that the different websites could share the same set of custom components. I then implemented a rough rebuild of anchorage.org.au. 

This repo was used as the basis for [the latest redesign](github.com/livinggracedianella/website-redesign), which has been a team effort rather than a solo one, and I have been a key player in this redesign at a project level and at a coding level.

## 🚀 Project Structure

```
/
├── shared-components/
├── websites/
│   ├── 68waverley/
│   ├── livinggracedianella/
│   └── shared-documentation/
│   └── theanchoragecollective/
```
