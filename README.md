<img src="https://raw.githubusercontent.com/scope42/scope42/main/app/public/logo.svg" width="100%" alt="scope42 logo">

<h1 align="center">Improve your software architecture with precision!</h1>

<p align="center">
  <a href="https://github.com/scope42/scope42/actions/workflows/build.yml"><img src="https://github.com/scope42/scope42/actions/workflows/build.yml/badge.svg" alt="Build"></a>
  <a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <a href="https://github.com/scope42/scope42/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-informational.svg" alt="License: GPL v3"></a>
  <a href="https://github.com/scope42/scope42/tree/main/architecture"><img src="https://img.shields.io/badge/%F0%9F%93%96%20architecture-scope42-blue" alt="Architecture Documentation" /></a>
  <br />
  <a href="https://matrix.to/#/#scope42:matrix.org"><img src="https://img.shields.io/matrix/scope42:matrix.org" alt="Matrix"></a>
  <a href="https://twitter.com/scope42_org"><img src="https://img.shields.io/twitter/follow/scope42_org?style=social" alt="Twitter Follow"></a>
  <a href="https://floss.social/@scope42"><img src="https://img.shields.io/mastodon/follow/108202636664253561?domain=https%3A%2F%2Ffloss.social&amp;style=social" alt="Mastodon Follow"></a>
</p>

This tool helps you to keep track of issues, arising risks and possible improvements of your existing architecture. The terminology and concepts are based on [aim42, the Architecture Improvement Method](https://www.aim42.org/).

scope42 is a Progressive Web App that runs entirely inside your browser. Click the link below to access the app.

<h3 align="center">🔗 <a href="https://app.scope42.org">app.scope42.org</a></h3>


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fscope42%2Fscope42.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fscope42%2Fscope42?ref=badge_large)

## Features

<h3 align="center">✨ Management of items with a fancy UI</h3>

<p align="center">
  Filtering • Sorting • Full text search • Learn about aim42
</p>

<img src="docs/screenshot-table.png" alt="Screenshot of item table">

<h3 align="center">💑 Graphs for visualizing the relationships between items</h3>

<p align="center">
  Quick overview • Drag & Drop • Navigate
</p>

<img src="docs/screenshot-graph.png" alt="Screenshot of item graph">

<h3 align="center">📝 Docs-as-Code principle and full data ownership</h3>
<p align="center">
  Human-readable • Check into version control • Process programatically • No vendor lock-in
</p>
<br />

```yaml
title: Upgrade Spring Boot version
created: 2022-05-02T17:25:16.909Z
modified: 2022-05-02T18:09:42.952Z
status: implemented
tags:
  - backend
  - urgent
  - security
ticket: https://github.com/scope42/scope42/issues/91
description: The current version of Spring Boot upgrades dependencies to secure
  versions of Log4j.
resolves:
  - issue-3
modifies:
  - risk-1
comments:
  - author: Jane Doe
    created: 2022-05-02T17:27:17.630Z
    content: Accepted and placed into the fast lane on the board.
```

## Planned Features

- WYSIWYG markdown editor
- Support for requirements (new item type)
- Support for prose documentation of existing architecture (based on arc42)
- Support for media files
- Customizable Dashboard
- Export structured data (convenience library)
- Export static site
- Export markdown

## Badge

[![Architecture Documentation](https://img.shields.io/badge/%F0%9F%93%96%20architecture-scope42-blue)](https://github.com/scope42/scope42/tree/main/architecture)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fscope42%2Fscope42.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fscope42%2Fscope42?ref=badge_shield)

If you use scope42 in your project, you can add this badge to your README. This way, people visiting your repository can quickly find the architecture documentation. Simply copy the code below and change the link to point to an export (coming soon) or the workspace of your scope42 data.

```md
[![Architecture Documentation](https://img.shields.io/badge/%F0%9F%93%96%20architecture-scope42-blue)](https://github.com/scope42/scope42/tree/main/architecture)
```

## Tech Stack

- [React](https://reactjs.org)
- [Ant Design](https://ant.design)
- [Cytoscape.js](https://js.cytoscape.org/)

## Develop

Contributions are always welcome!

### `npm start`

Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits. You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

## License

scope42 is published under the [GNU General Public License v3.0](https://github.com/scope42/scope42/blob/main/LICENSE).

The data model and basic concepts are based on the [aim42 Method Reference](https://aim42.github.io/) by [Gernot Starke](https://www.gernotstarke.de/) and community contributors, used under [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/).

scope42 is not affiliated with aim42.