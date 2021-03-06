---
layout: app

permalink: /Lepton/
description: Democratizing Code Snippets Management (macOS/Win/Linux)
license: NOASSERTION

icons:
  - Lepton/icons/128x128/lepton.png

screenshots:
  - Lepton/screenshot.png

authors:
  - name: hackjutsu
    url: https://github.com/hackjutsu

links:
  - type: GitHub
    url: hackjutsu/Lepton
  - type: Download
    url: https://github.com/hackjutsu/Lepton/releases

desktop:
  Desktop Entry:
    Name: Lepton
    Comment: Democratizing Code Snippets Management (macOS/Win/Linux)
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: lepton
    X-AppImage-Version: 1.7.2-beta.1
    X-AppImage-BuildId: 6a56f8a0-a75a-11a8-38ee-bf4fd7c9bb91
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: NOASSERTION

electron:
  productName: Lepton
  main: main.js
  repository:
    type: git
    url: https://github.com/hackjutsu/Lepton.git
  author: CosmoX
  license: MIT
  dependencies:
    autolinker: "^1.4.0"
    bluebird: "^3.4.7"
    chart.js: "^1.1.1"
    codemirror: "^5.28.0"
    electron-context-menu: "^0.9.0"
    electron-is-dev: "^0.3.0"
    electron-json-storage-sync: "^1.1.0"
    electron-localshortcut: "^3.0.0"
    electron-updater: 2.18.2
    electron-window-state: "^4.1.1"
    fuse.js: "^3.0.0"
    highlight.js: "^9.9.0"
    highlightjs-solidity: "^1.0.6"
    human-readable-time: "^0.3.0"
    image-downloader: "^3.2.1"
    markdown-it: "^8.3.2"
    markdown-it-katex: "^2.0.3"
    markdown-it-task-lists: "^2.0.1"
    moment: "^2.20.1"
    nconf: "^0.10.0"
    notebookjs: "^0.3.1"
    prismjs: "^1.15.0"
    proxy-agent: "^3.0.1"
    react: "^16.2.0"
    react-bootstrap: "^0.32.1"
    react-chartjs: "^1.2.0"
    react-codemirror: "^1.0.0"
    react-dom: "^16.2.0"
    react-redux: "^5.0.6"
    react-split-pane: "^0.1.66"
    redux: "^3.7.2"
    redux-form: "^7.0.0"
    redux-thunk: "^2.1.0"
    request: "^2.88.0"
    request-promise: "^4.2.2"
    twitter-text: "^2.0.2"
    valid-filename: "^2.0.1"
    webpack-cli: "^3.1.0"
    winston: "^2.3.0"
---
