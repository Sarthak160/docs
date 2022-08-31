<div align="center">
<h1>Keploy</h1>
</div>
<p style="text-align:center;" align="center">
  <img align="center" src="https://avatars.githubusercontent.com/u/92252339?s=200&v=4" height="30%" width="30%" />
 <div align="center">
 <h1>Docs Website</h1>
 <p>
Repository for the Keploy docs website.
</p>
</div>
</p>

<p align="center">
<a href="https://github.com/keploy/docs" alt="GitHub contributors">
<img src="https://img.shields.io/github/contributors/keploy/docs.svg" /><a>
<a href="https://github.com/keploy/docs" alt="GitHub issues by-label">
<img src="https://img.shields.io/github/issues/keploy/docs" /></a>
<a href="https://keploy.slack.com/" alt="Slack">
<img src="https://img.shields.io/badge/Slack-@layer5.svg?logo=slack" /></a>
<a href="https://twitter.com/Keployio" alt="Twitter Follow">
<img src="https://img.shields.io/twitter/follow/keploy.svg?label=Follow&style=social" /></a>
<a href="https://github.com/keploy/docs" alt="License">
<img src="https://img.shields.io/github/license/keploy/docs.svg" /></a>
</p>

[Keploy](https://keploy.io) is a no-code testing platform that generates tests from API calls.

Keploy is constantly working to improve and expand its documentation.
Some components may change without notice.
Page slugs (URLs), menu labels, and the location of information are a few of the items you can expect to see altered as we endeavor to give you the best experience possible.

The documentation in this repository is published to https://docs.keploy.io.

If information you are looking for seems to be missing, visit the [Keploy community](https://join.slack.com/t/keploy/shared_invite/zt-12rfbvc01-o54cOG0X1G6eVJTuI_orSA/) forum for help.

Please read the [CONTRIBUTING](/CONTRIBUTING.md) guide and the [STYLE](/STYLE.md) guide before you submit any pull requests.

Maintainers and contributors to this project are expected to conduct themselves in a respectful way.
See the [CNCF Community Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md) as a reference.

## Technology Stack

We use a variety of technologies to build the web interface and support the community. They include:

- [NodeJS](https://nodejs.org/)
- [Yarn package manager](https://yarnpkg.com/)
- [Docusaurus](https://docusaurus.io/)
- [React](https://reactjs.org/)
- [GitHub Actions](https://github.com/features/actions)

We use NodeJS and Yarn to install, test, and build the website. Docusaurus has been used as a static site generator to build the website. React is being utilized to build our custom component-based user interface to provide a modern look to the website. GitHub Actions manages our CI/CD pipelines and issue triage.

## ## Installation

The Keploy documentation site uses [Docusaurus 2](https://v2.docusaurus.io/), which is a static website generator.

You can make changes locally without previewing them in the browser.
However, if you want to build the site and preview changes in the browser, you need to have [Docusaurus 2 dependencies](https://v2.docusaurus.io/docs/installation/#requirements) installed.

Initialize Docusaurus 2 in the repo by running [`yarn`](https://classic.yarnpkg.com/en/docs/cli/) once in the root directory of the repo.

Now you can build and view the site locally:

```bash
yarn start
```

The command starts a local development server and opens a browser window.

## Prettier

1. Fork the repository

<br/>

2. Clone the repository with the following command. Replace the <GITHUB_USERNAME> with your username

```sh
git clone https://github.com/<GITHUB_USERNAME>/community-website.git
```

<br/>

3. Go into the directory containing the project

```sh
cd docs
```

<br/>

4. Install all the dependencies

```sh
yarn
```

<br/>

5. Start the development server.

```sh
yarn start
```

6. To reformat:

```
yarn prettier --write '**/*.{js,md}'
```

When we merge your PR, a new build automatically occurs and your changes publish to [https://docs.keploy.io](https://docs.keploy.io).

## How to Get Involved?

Keploy welcomes contributions to the docs website. If you have an idea for a new feature or a bug fix, please submit an issue or pull request. Our planned features can be found on our [Issue Tracker](https://github.com/keploy/docs/issues/new/choose).

## Community support

We'd love to collaborate with you to make Keploy great. To get started:

- [Slack](https://join.slack.com/t/keploy/shared_invite/zt-12rfbvc01-o54cOG0X1G6eVJTuI_orSA) - Discussions with the community and the team.
- [GitHub](https://github.com/keploy/keploy/issues) - For bug reports and feature requests.

## 📌 Our valuable Contributors 👩‍💻👨‍💻 :

<table>
  <tr>
    <a href="https://github.com/keploy/docs/graphs/contributors">
      <img src="https://contrib.rocks/image?repo=keploy/docs" />
    </a>
  </tr>
</table>
