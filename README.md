# Copier Flexlate Dev Semantic Release

Copier template to generate a Copier template using Flexlate Development Tools and Semantic Release

Automatically publishes example repositories.

## Initial Setup

First generate the Flexlate Development Tools config file by serving and saving:

```
dfxt serve -s
```

Then stop it and adjust the config file as needed.

## Development Status

This project uses [semantic-release](https://github.com/semantic-release/semantic-release) for versioning.
Any time the major version changes, there may be breaking changes. If it is working well for you, consider
pegging to the current major version, e.g. `copier-flexlate-dev-semantic-release@v1`, to avoid breaking changes. Alternatively,
you can always point to the most recent stable release with the `copier-flexlate-dev-semantic-release@latest`.

## Developing

Clone the repo and then run `npm install` to set up the pre-commit hooks.

## Author

Created by Nick DeRobertis. MIT License.
