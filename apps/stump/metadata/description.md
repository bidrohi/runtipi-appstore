<p align="center">
  <img alt="Stump's logo. Description: A young individual sitting on a tree stump reading a book. Inspired by Stump's creator's childhood, where a large amount of his time was spent sitting on a tree stump reading his comic books." src="https://raw.githubusercontent.com/stumpapp/stump/refs/heads/main/.github/images/logo.png" style="width: 50%" />
  <br />
  <a href="https://github.com/awesome-selfhosted/awesome-selfhosted#document-management---e-books">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Self-Hosted">
  </a>
  <a href="https://discord.gg/63Ybb7J3as">
    <img src="https://img.shields.io/discord/972593831172272148?label=Discord&color=5865F2" />
  </a>
  <a href="https://github.com/stumpapp/stump/blob/main/LICENSE">
    <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=CF9977" />
  </a>
  <a href="https://hub.docker.com/r/aaronleopold/stump">
    <img src="https://img.shields.io/docker/pulls/aaronleopold/stump?logo=docker&color=0aa8d2&logoColor=fff" alt="Docker Pulls">
  </a>
</p>

<p align='center'>
Stump is a free and open source comics, manga and digital book server with OPDS support, created with <a href="https://www.rust-lang.org/">Rust</a>, <a href='https://github.com/tokio-rs/axum'>Axum</a>, <a href='https://github.com/Brendonovich/prisma-client-rust'>Prisma</a> and <a href='https://reactjs.org/'>React</a>.
</p>

<p align='center'>
<img alt="Screenshot of Stump" src="https://raw.githubusercontent.com/stumpapp/stump/refs/heads/main/.github/images/demo.png" style="width: 90%" />
</p>

> **🚧 Disclaimer 🚧**: Stump is under active development and is an ongoing **WIP**. Anyone is welcome to try it out, but **DO NOT** expect a fully featured or bug-free experience. If you'd like to contribute and help expedite feature development, please review the [developer guide](#developer-guide-).

## Roadmap 🗺

The following items are the major targets for Stump's first stable release:

- 📃 Full OPDS + OPDS Page Streaming support
- 📕 EPUB, PDF, and CBZ/CBR support
- 📚 Organize libraries with collections and reading lists
- 🔐 Granular access-control with managed user accounts
- 🚀 Easy setup and deployment using Docker or bare metal
- 👀 Fully responsive, built-in UI with a dark mode
- 🏃 Low resource utilization with excellent performance
- 🧰 Easily consumable and documented REST API, so community tools and scripts can interact with Stump
- 🌏 Language support _(look [here](https://github.com/stumpapp/stump/issues/106))_
- 🌈 And more!

Things you can expect to see afterwards:

- 🖥️ Cross-platform desktop app _(Windows, Mac, Linux)_
- 📱 In-house mobile app _(Android, iOS)_
- 🔎 Versatile full-text search _(blocked by [prisma#9414](https://github.com/prisma/prisma/issues/9414))_
- 👥 Configurable book clubs _(see [this issue](https://github.com/stumpapp/stump/issues/120))_

Feel free to reach out if you have anything else you'd like to see!

## Apps

Stand-alone applications that can be run independently, at `/apps` in the root of the project:

- `desktop`: A React + Tauri desktop application
- `expo`: A React Native application ([#125](https://github.com/stumpapp/stump/issues/125))
- `server`: An [Axum](https://github.com/tokio-rs/axum) HTTP server
- `web`: A React application, the primary UI for both the built-in web app the server serves and the desktop app

The only exception to this is the `docs` app, which is a NextJS application and is located at `/docs` in the root of the project.

## License 📝

Stump is broken up into a number of different packages and applications. Some of these have their own licenses. For example, the `expo` app is licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html). If a package has its own license, it will be noted in the package's README or LICENSE file. In such cases, the license file(s) in the subfolder/package take precedence. If such a license or disclaimer is not present, it is safe to assume that the code is licensed under the [MIT License](https://www.tldrlegal.com/license/mit-license).

## Folder Info

| Root Folder                               | Container Folder |
|-------------------------------------------|------------------|
| /runtipi/app-data/stump/data/config       | /config          |
| /runtipi/media/data                       | /media           |
