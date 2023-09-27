<img src=".erb/img/erb-banner.svg" width="100%" />

<br>

<p>
  Electron React Boilerplate uses <a href="https://electron.atom.io/">Electron</a>, <a href="https://facebook.github.io/react/">React</a>, <a href="https://github.com/reactjs/react-router">React Router</a>, <a href="https://webpack.js.org/">Webpack</a> and <a href="https://www.npmjs.com/package/react-refresh">React Fast Refresh</a>.
</p>

<br>

<div align="center">

[![Build Status][github-actions-status]][github-actions-url]
[![Github Tag][github-tag-image]][github-tag-url]
[![Discord](https://badgen.net/badge/icon/discord?icon=discord&label)](https://discord.gg/Fjy3vfgy5q)

[![OpenCollective](https://opencollective.com/electron-react-boilerplate-594/backers/badge.svg)](#backers)
[![OpenCollective](https://opencollective.com/electron-react-boilerplate-594/sponsors/badge.svg)](#sponsors)
[![StackOverflow][stackoverflow-img]][stackoverflow-url]

</div>

## Install

Clone the repo and install dependencies:

```bash
git clone https://github.com/yale-swe/f23-handedit-pro handedit-pro
cd handedit-pro
npm install
```

## Starting Development
1. Install "Eslint" extension in VSCode.
2. Turn on "Format on Save" in VSCode settings. [How to do this?](https://stackoverflow.com/questions/39494277/how-do-you-format-code-on-save-in-vs-code)
3. Start the app in the `dev` environment:
```bash
npm start
```

## Packaging for Production

To package apps for the local platform:

```bash
npm run package
```
## Pre-push hooks
We use [husky](https://typicode.github.io/husky/) to run pre-push hooks.  
This will build the app and run the linter and tests before pushing to the remote repository.  
Please do not push to the remote repository if the pre-push hooks fail.

## GitHub Actions
