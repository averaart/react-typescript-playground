# Quickstart for React

Mostly a combination of the [React and Webpack](https://www.typescriptlang.org/docs/handbook/react-&-webpack.html0) example on the TypeScript website and [instructions by Robin Rendle](https://gist.github.com/robinrendle/0bb0b9e55fafa1cc0c64ff4b5776df050).

- Run `yarn install`
- Run `yarn start`
- Chrome will open, load `index.html` and will reload after any compile

## Create duplicate repo able to merge updates

- `git clone git@github.com:averaart/react-typescript-playground.git my-new-playground`
- `cd my-new-playground`
- `git remote set-url origin git@github.com:<username>/<my-new-playground>.git`
- `git push`
- `git remote add base-playground git@github.com:averaart/react-typescript-playground.git`
- `git fetch base-playground`

Pull in updates to the original repo:

- `git fetch base-playground`
- `git merge --no-ff --no-edit base-playground/master`

## Todo

- figure out if there's any actual difference between `yarn dev` and `yarn start`, as they both seem to compile and reload on changes.