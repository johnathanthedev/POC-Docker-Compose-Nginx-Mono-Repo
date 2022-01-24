<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
<!--   <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">POC: Docker Compose - Nginx - Mono Repo</h3>

  <p align="center">
    A template for setting up a local reverse proxy with Docker Compose and Nginx.
    <br />
    <a href="https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/issues">Report Bug</a>
    ·
    <a href="https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

There are many resources on the web for setting up Nginx as a reverse proxy for web applications. However, I did not find enough documentation on having multiple different frontends and backends configured with our Nginx server. This alone is what motivated me to build a template that serves as a reference for not just one application but many.

Here's why:
* Focus more on your code rather than setting up your environment
* Learn about multiple applications under one domain 

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this template!

### Built With

*Working on adding support for more technologies*

* [React.js](https://reactjs.org/)
* [Nginx](https://www.nginx.com/)
* [Docker](https://www.docker.com/)

<!-- GETTING STARTED -->
## Getting Started

Starting off, you will need some things installed on your machine.

### Prerequisites

* Npm
* Node
* Nginx
* Docker
* Docker-compose

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo.git
   ```
   
2. cd into cloned repo
   ```sh
   cd POC-Docker-Compose-Nginx-Mono-Repo
   ```
   
3. Get latest
   ```sh
   git submodule update --init --recursive
   git submodule foreach git checkout main
   git submodule foreach git pull origin main
   ```
   
4. Start up server
    ```sh
    docker-compose up --build
    ```
    
5. Head to http://localhost:8080/
   
<!-- USAGE EXAMPLES -->
## Usage

The best way to utilize this repository would be as a reference point when working with docker-compose and nginx in your local machine.

<!-- ROADMAP -->
## Roadmap

- [ ] Add Rails API + Postgresl support
- [ ] Add Rails API + Mysql support
- [ ] Add Rails API + MongoDB support
- [ ] Add Node/Express API + Postgresl support
- [ ] Add Node/Express API + Mysql support
- [ ] Add Node/Express API + MongoDB support
- [ ] Add Vue support
- [ ] Add static html support
- [ ] Add webpack support


See the [open issues](https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/issues) for a full list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact

Johnathan Guzman - [@snorlax_dev](https://twitter.com/snorlax_dev) - johnathanthedev@gmail.com

Project Link: [https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo](https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo)

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo.svg?style=for-the-badge
[contributors-url]: https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo.svg?style=for-the-badge
[forks-url]: https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/network/members
[stars-shield]: https://img.shields.io/github/stars/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo.svg?style=for-the-badge
[stars-url]: https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo.svg?style=for-the-badge
[issues-url]: https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/issues
[license-shield]: https://img.shields.io/github/license/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo.svg?style=for-the-badge
[license-url]: https://github.com/johnathanthedev/POC-Docker-Compose-Nginx-Mono-Repo/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/johnathan-guzman
[product-screenshot]: images/screenshot.png
