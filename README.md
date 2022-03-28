# ht.reactjs.org 🇭🇹

This repo contains the source code and documentation powering [ht.reactjs.org] which is the Haitian Creole translation of [reactjs.org](https://reactjs.org).

## Getting started

### Prerequisites

1. Git
1. Node: any 12.x version starting with v12.0.0 or greater
1. Yarn: See [Yarn website for installation instructions](https://yarnpkg.com/lang/en/docs/install/)
1. A fork of the repo (for any contributions)
1. A clone of the [reactjs.org repo](https://github.com/reactjs/reactjs.org) on your local machine

### Installation

1. `cd ht.reactjs.org` to go into the project root
1. `yarn` to install the website's npm dependencies

### Running locally

1. `yarn dev` to start the hot-reloading development server (powered by [Gatsby](https://www.gatsbyjs.org))
1. `open http://localhost:8000` to open the site in your favorite browser

## Contributing


### Translation

If you are interested in translating `reactjs.org` to **Haitian Creole**, check the translation progress **[here](https://github.com/reactjs/ht.reactjs.org/issues/1)**. Also, when translating any content, make sure to follow our **[Glossary](GLOSSARY.md)**.

### Guidelines
You've cloned the repo, created your branch, and are armed with your favorite beverage to power you through a coding sprint, now what. The following diagram, highlights the primary files and directories you will modify in order to successfully translate documentation that gets rendered on the site.

```
.
├── CODE_OF_CONDUCT.md
├── GLOSSARY.md
├── README.md
├── content
│   ├── home/
│   ├── docs/
│   ├── blog/
│   ├── tutorial/
│   ├── 404.md
│   ...
├── src
│   ├── pages/
│   ...
```

The documentation is divided into several sections with a different tone and purpose. If you plan to write more than a few sentences, you might find it helpful to get familiar with the [contributing guidelines](https://github.com/reactjs/reactjs.org/blob/main/CONTRIBUTING.md#guidelines-for-text) for the appropriate sections.

### Create a branch

1. `git checkout main` from any folder in your local `reactjs.org` repository
1. `git pull origin main` to ensure you have the latest main code
1. `git checkout -b the-name-of-my-branch` (replacing `the-name-of-my-branch` with a suitable name) to create a branch

### Make the change

1. Follow the ["Running locally"](#running-locally) instructions
1. Save the files and check in the browser
  1. Changes to React components in `src` will hot-reload
  1. Changes to markdown files in `content` will hot-reload
  1. If working with plugins, you may need to remove the `.cache` directory and restart the server

### Test the change

1. If possible, test any visual changes in all latest versions of common browsers, on both desktop and mobile.
1. Run `yarn check-all` from the project root. (This will run Prettier, ESLint, and Flow.)

### Push it

1. `git add -A && git commit -m "My message"` (replacing `My message` with a commit message, such as `Fix header logo on Android`) to stage and commit your changes
1. `git push my-fork-name the-name-of-my-branch`
1. Go to the [reactjs.org repo](https://github.com/reactjs/reactjs.org) and you should see recently pushed branches.
1. Follow GitHub's instructions.
1. If possible, include screenshots of visual changes. A preview build is triggered after your changes are pushed to GitHub.

<<<<<<< HEAD
=======
## Translation

If you are interested in translating `reactjs.org`, please see the current translation efforts at [translations.reactjs.org](https://translations.reactjs.org/).


If your language does not have a translation and you would like to create one, please follow the instructions at [reactjs.org Translations](https://github.com/reactjs/reactjs.org-translation#translating-reactjsorg).

>>>>>>> 5e9d673c6bc1530c901548c0b51af3ad3f91d594
## Troubleshooting

- `yarn reset` to clear the local cache

## Progress 🚧👷🏼👷🏿👷‍♀️🚧

* ❌ Home Page
* ❌ Tutorial
* ❌ Hello World
* ❌ Introducing JSX
* ❌ Rendering Elements
* ❌ Components and Props
* ❌ State and Lifecycle
* ❌ Handling Events
* ❌ Conditional Rendering
* ❌ Lists and Keys
* ❌ Forms
* ❌ Lifting State Up
* ❌ Composition vs Inheritance
* ❌ Thinking in React
* ❌ React
* ❌ React.Component
* ❌ ReactDOM
* ❌ ReactDOMServer
* ❌ DOM Elements
* ❌ SyntheticEvent
* ❌ Test Utilities
* ❌ Shallow Renderer
* ❌ Test Renderer
* ❌ JS Environment Requirements
* ❌ Glossary
* ❌ tutorial/nav.yml
* ❌ docs/nav.yml

## License
Content submitted to [reactjs.org](https://reactjs.org/) is CC-BY-4.0 licensed, as found in the [LICENSE-DOCS.md](https://github.com/open-source-explorer/reactjs.org/blob/master/LICENSE-DOCS.md) file.
