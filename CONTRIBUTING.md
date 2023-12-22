# Contributing

We are open to, and grateful for, any contributions made by the community. By contributing to axios, you agree to abide by the [code of conduct](https://github.com/axios/axios/blob/main/CODE_OF_CONDUCT.md).

## Code Style

Please follow the [node style guide](https://github.com/felixge/node-style-guide).

## Commit Messages

Please follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

## Testing
<<<<<<< HEAD

Please update the tests to reflect your code changes. Pull requests will not be accepted if they are failing on GitHub actions.

=======

Please update the tests to reflect your code changes. Pull requests will not be accepted if they are failing on [Travis CI](https://travis-ci.org/axios/axios).

>>>>>>> 9588fcdec8aca45c3ba2f7968988a5d03f23168c
## Documentation

Please update the [docs](README.md) accordingly so that there are no discrepancies between the API and the documentation.

## Developing

- `npm run test` run the jasmine and mocha tests
- `npm run build` run webpack and bundle the source
- `npm run version` prepare the code for release

Please don't include changes to `dist/` in your pull request. This should only be updated when releasing a new version.

<<<<<<< HEAD
=======
## Releasing

Releasing a new version is mostly automated. For now the [CHANGELOG](https://github.com/axios/axios/blob/main/CHANGELOG.md) requires being updated manually. Once this has been done run the commands below. Versions should follow [semantic versioning](http://semver.org/).

- `npm version <newversion> -m "Releasing %s"`
- `npm publish`

>>>>>>> 9588fcdec8aca45c3ba2f7968988a5d03f23168c
## Running Examples

Examples are included in part to allow manual testing.

Running example

```bash
> npm run examples
# Open 127.0.0.1:3000
```

Running sandbox in browser

```bash
> npm start
# Open 127.0.0.1:3000
```

Running sandbox in terminal

```bash
> npm start
> node ./sandbox/client
```
