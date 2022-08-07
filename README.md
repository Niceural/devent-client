<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

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
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://solana.com/summercamp">
    <img src="images/solana-hackathon.svg" alt="Logo" width="500">
  </a>

<h3 align="center">devent</h3>

  <p align="center">
    A decentralized event management and ticketing application
    <!-- <br />
    <a href="https://github.com/Niceural/devent"><strong>Explore the docs »</strong></a>
    <br /> -->
    <br />
    <a href="https://youtube.com/">View Demo</a>
    ·
    <a href="https://github.com/Niceural/devent/issues">Report Bug</a>
    ·
    <a href="https://github.com/Niceural/devent/issues">Request Feature</a>
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

<!-- screenshots -->

This project consists in a decentralized application where users can create events, register to events, and more. It can be considered as a dummy web3 implementation of [eventbrite](https://www.eventbrite.co.uk/). The program (or smart contract) is deployed on [Solana](https://solana.com/) devnet. It has been submitted for examination by the [Solana Summer Camp Hackathon](https://solana.com/summercamp) judges. This project implements the following features:

- an organizer can create a new event (with metadata stored off chain and arbitrary ticket price),
- a wallet can register to an event (and pay in SOL if not free),
- a wallet can confirm attendance to an event,
- a wallet can receive an NFT on registration and/or attendance to the event,
- an organizer can choose to allow a wallet to resell its ticket and set a maximum resell price,

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [IPFS](https://ipfs.tech/)
- [Pinata](https://www.pinata.cloud/)
- [Tailwindcss](https://tailwindcss.com/)
- [Anchor](https://www.anchor-lang.com/)
- [Solana](https://solana.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

In this section we will discuss how to setup and run this project's frontend locally.

### Prerequisites

Project prerequisites and links to how to install them:

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [yarn](https://classic.yarnpkg.com/en/docs/install#debian-stable)
- [git](https://git-scm.com/downloads)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Niceural/devent.git
   cd devent/devent-frontend/
   ```
2. Install NPM packages
   ```sh
   yarn
   ```
3. Create an account and create a new Pinata API key at [this](https://app.pinata.cloud/keys) link
4. Create a [.env](./devent-frontend/.env) file and enter your API and API secret keys following [.env.example](./devent-frontend/.env.example) template:
   ```sh
   touch .env
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

### Create a new event

### Show all events

### Register for an event

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [ ] README
- [ ] youtube presentation video
- [ ] program
  - [ ] integration tests
    - [ ] create a new event with off chain metadata
    - [ ] get all events
    - [ ] register to an event
  - [ ] unit tests
    - [ ] create state
    - [x] state
    - [x] create event with metadata off chain
    - [ ] create event with metadata on chain
    - [ ] attendee registers and transfer lamports
    - [ ] mint nft on registration
    - [ ] confirm attendance
    - [ ] mint nft on attendance registration
    - [ ] resell ticket with fixed price
    - [ ] resell ticket with custom price
- [ ] frontend
  - [ ] home page
  - [ ] create a new event page
    - [ ] store file image with pinata
    - [ ] store metadata with pinata
    - [ ] store file image with nft.storage
    - [ ] store metadata with nft.storage
    - [ ] store metadata on chain
  - [ ] all events page
  - [ ] register for event page

See the [open issues](https://github.com/Niceural/devent/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

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

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See [LICENSE.txt](./LICENSE.txt) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Your Name - [@Niceural](https://twitter.com/Niceural) - nicolas.bayle20@imperial.ac.uk

Project Link: [https://github.com/Niceural/devent](https://github.com/Niceural/devent)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- []()
- []()
- []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/Niceural/devent.svg?style=for-the-badge
[contributors-url]: https://github.com/Niceural/devent/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Niceural/devent.svg?style=for-the-badge
[forks-url]: https://github.com/Niceural/devent/network/members
[stars-shield]: https://img.shields.io/github/stars/Niceural/devent.svg?style=for-the-badge
[stars-url]: https://github.com/Niceural/devent/stargazers
[issues-shield]: https://img.shields.io/github/issues/Niceural/devent.svg?style=for-the-badge
[issues-url]: https://github.com/Niceural/devent/issues
[license-shield]: https://img.shields.io/github/license/Niceural/devent.svg?style=for-the-badge
[license-url]: https://github.com/Niceural/devent/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/nicolas-bayle-558a21200
