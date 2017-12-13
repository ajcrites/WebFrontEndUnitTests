# Web Frontend Unit Testing Mobiquity Practices

This repository is an example and teaching tool for the
creation of web frontend unit tests with AngularJS (v1).

The point of this repository is not necessarily show how to
create and test an AngularJS app specifically, but to show
examples of tools and processes used for creating unit
tests with web frontend apps.

## Installation

Install nodejs and npm. I recommend using [`n`](https://github.com/tj/n)
for managing node version installations, but feel free to install it
from source or use a package manager like `brew`. This should work for
most versions of nodejs including the latest (9).

Install [`yarn`](https://yarnpkg.com/en/) with `brew install yarn`.

Once nodejs is installed, run `yarn install` to install the
dependencies for the projects. Now you're ready to start
testing.

## Development and Testing
You can start the app with `yarn start`. Then you can access the calculator
on localhost:3000.

You can run the tests with `yarn test`. This will display the output of the
tests in the command line and create a coverage report in the `coverage`
directory.
