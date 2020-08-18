# Eleventy Starter [![Netlify Status](https://api.netlify.com/api/v1/badges/4eb519eb-9518-4b07-bd0a-f7a5610d3ee3/deploy-status)](https://app.netlify.com/sites/ideas42ventures-eleventy-starter/deploys)

A very opinionated static site project scaffold with Eleventy. Made for use as a GitHub template repo.

## How to use this repo

TODO

---

## Environments

- (✏️ CHANGE ME FOR YOUR PROJECT) Production: [ideas42ventures-eleventy-starter.netlify.app/](https://ideas42ventures-eleventy-starter.netlify.app/)
- Staging: Every pull request gets a preview deploy URL. Check the PR or Netlify UI for it.

## Contributing

- This is a static site build using [Eleventy](https://www.11ty.dev/docs)
- Hosted on Netlify

### Requirements

- node.js: LTS version recommended
- yarn: Latest version recommended

### Local setup

#### Clone the repo

(✏️ CHANGE ME FOR YOUR PROJECT)

```
git clone git@github.com:orgname/repo-name.git
cd repo-name
```

#### Install dependencies

```
yarn
```

#### Start the dev server and watcher

```
yarn start
```

The site will be available at [http://localhost:8080/](http://localhost:8080/).

#### Build without dev server or watcher

When you need to do a new build without starting the dev server or file watchers run:

```
yarn build
```

## Deploying

### To Production

We host this site on [Netlify](https://www.netlify.com/). Anything merged into the `main` branch is deployed to production.

### To Staging

We use Netlify preview builds. To see any branch in a live environment, push the branch to the remote and open a pull request.

## Code formatting

We format all JavaScript, CSS, and HTML with [Prettier](https://prettier.io). We use the [lint-staged with husky approach](https://prettier.io/docs/en/precommit.html#option-1-lint-stagedhttpsgithubcomokonetlint-staged) to make sure formatting happens for all contributors.
