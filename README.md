# The Grand Tour
Semester-long project for LMC 6340: Reality Experience Design

## Prerequisites
1. Have Node 16.13.1 installed

## Setup
1. `npm i` to install dependencies.

## Development
`npm run check` will typecheck your code using `tsc`. Does not output any files, though.

`npm run compile` will run `npm run check`, and also bundle all of the code together using [esbuild](https://github.com/evanw/esbuild).