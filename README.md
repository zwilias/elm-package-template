# Elm package template

Template for creating a new Elm package, with tests, verified examples and travis integration.

## Getting started

Globally install `elm-test`, `elm-verify-examples` and `elm-format@exp`

```sh
npm i -g elm-test elm-verify-examples elm-format@exp
```

Now, clone this repo, rename it and make it your own:

```sh
git clone git@github.com:zwilias/elm-package-template.git &&
  mv elm-package-template my-elm-module &&
  cd my-elm-module &&
  rm -rf .git &&
  git init &&
  git add . &&
  git commit -m "Initial commit"
```

Good!

Now edit `elm-package.json` to set the repo and description to whatever you need.
Once you've done that, start editing!

## Running tests and verifying your examples:

```sh
elm-verify-examples && elm-test
```
