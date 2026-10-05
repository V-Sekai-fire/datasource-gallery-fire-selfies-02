# datasource-gallery-fire-selfies-02

A photo gallery of K. S. Ernest (iFire) Lee's selfies, built into a static site on each push to the default branch.

## What it is for

The photos live in `gallery/`, and the workflow builds the site from them with the thumbsup gallery generator reading `config.json`, then publishes it to the repository's pages site.

## Build

```sh
thumbsup --config config.json
```

## Licence

All rights reserved; see `LICENSE`.
