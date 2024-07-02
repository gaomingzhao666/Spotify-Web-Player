<a name="readme-top"></a>

[![Stargazers][stars-shield]][stars-url]
[![Apache2.0 License][license-shield]][license-url]

🚫 This project, which relies on the server-side APIs provided by [NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi), is no longer under development. This is because the server-side support APIs has been officially deleted, making it impossible to add new features or improve existing functionalities that depend on these APIs. As a result, Spotify-Web-Player is no longer maintained.

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/gaomingzhao666/Spotify-Web-Player">
    <img src="/public/logo.svg" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">Spotify Web Player</h3>

  <p align="center">
    🎵 Web music platform developed based on Spotify UI/UX 🎵
    <br />
    <br />
    <a href="https://github.com/gaomingzhao666/Spotify-Web-Player/blob/master/README-EN.md">English</a>
     <strong> · </strong>
    <a href="https://github.com/gaomingzhao666/Spotify-Web-Player/blob/master/README.md">简体中文</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Directory</summary>
  <ul>
    <li><a href="#introduction-of-project">Introduction of Project</a> </li>
    <li><a href="#build-with">Build With</a></li>
    <li><a href="#environment-requirement">Environment Requirement</a></li>
    <li><a href="#installation-and-usage---server">Installation and Usage - Server</a></li>
    <li><a href="#installation-and-usage---frontend">Installation and Usage - Frontend</a></li>
    <li><a href="#resolve-cors-problem">Resolve CORS Problem</a></li>
    <li><a href="#contributor">Contributor</a></li>
    <li><a href="#ui-design-reference">UI design Reference</a></li>
    <li><a href="#license">LICENSE</a></li>
  </ul>
</details>

<!-- ABOUT THE PROJECT -->

## Introduction of Project

<p align="center">
    <img src="/SCREENSHOT/index-mockup.png">
</p>

> The image shown here is a index-page for tablet-size, [click here](https://github.com/gaomingzhao666/Spotify-Web-Player/tree/main/SCREENSHOT) to see more detailed screenshot for this application.

A web music player UI/UX clone from Spotify Web Player AND data-source provided by NetEaseCloud Music

<p align="right"> (<a href="#readme-top">back to top</a>)</p>

## Build With

- Vue3 with composition API
- Vue-router
- Pinia
- Vite
- Less
- Element-plus
- ES6+
- Fetch

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Environment Requirement

- NodeJS LTS16+
- Chrome67+ / Edge79+ / Safari12+
- suitable device size, such as a PC or laptop

## Installation and Usage - Server

```sh
# clone the data-source support
git clone https://github.com/Binaryify/NeteaseCloudMusicApi.git
cd NeteaseCloudMusicApi
node app.js
```

## Installation and Usage - Frontend

```sh
# clone this project
git clone https://github.com/gaomingzhao666/Spotify-Web-Player.git
# install dependencies and run it
# recommend pnpm as a package manager that more faster than npm and the grammar is similar with npm
pnpm install
pnpm run dev
```

## Resolve CORS Problem

##### As a default, Because the CORS access has been not activated, Probably cannot use this project or there is no data has been loaded, There is several methods to resolve that problem

- use browser extension
- set CORS access when sending requests on the client side
- set CORS access when code interface on the Server side
- use builder such as webpack/vite etc

##### We use the first method as an instance

Recommend [Allow CORS](https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf) extension, Activate it when the setup is done, Of course, you can choose another extension or method to resolve that problem

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## UI Design Reference

[YouTube](https://www.youtube.com)
[Spotify](https://www.spotify.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributor

The project developed by [gaomingzhao666@Nano](https://github.com/gaomingzhao666)， there is the data-source support (unmaintained now)- [NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## LICENSE

[Apache License 2.0](https://github.com/gaomingzhao666/Spotify-Web-Player/blob/main/LICENSE)

gaomingzhao666/Spotify-Web-Player is licensed under the Apache License 2.0. A permissive license whose main conditions require preservation of copyright and license notices. Contributors provide an express grant of patent rights. Licensed works, modifications, and larger works may be distributed under different terms and without source code.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[stars-shield]: https://img.shields.io/github/stars/gaomingzhao666/Spotify-Web-Player?style=for-the-badge
[stars-url]: https://github.com/gaomingzhao666/Spotify-Web-Player/stargazers
[license-shield]: https://img.shields.io/hexpm/l/apa?style=for-the-badge
[license-url]: https://github.com/gaomingzhao666/Spotify-Web-Player/blob/main/LICENSE
[release-shield]: https://img.shields.io/github/v/release/gaomingzhao666/spotify-web-player?style=for-the-badge
[release-url]: https://github.com/gaomingzhao666/Spotify-Web-Player/releases/tag
