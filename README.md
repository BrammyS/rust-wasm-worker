<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![Stargazers][stars-shield]][stars-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/BrammyS/rust-wasm-worker">
    <img src="https://cdn.brammys.com/screenshots/2022/02/rustacean-flat-happy.png" alt="Logo" width="120" height="120">
  </a>

  <h3 align="center">Rust Webassembly Worker</h3>

  <p align="center">
    A really basic <a href="https://workers.cloudflare.com/">Cloudflare worker</a> made in rust.
    <br />
    <br />
    <a href="https://rust-wasm-worker.brammys.com">View Demo</a>
    ·
    <a href="https://github.com/BrammyS/rust-wasm-worker/issues">Report Bug</a>
    ·
    <a href="https://github.com/BrammyS/rust-wasm-worker/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

A really basic and mimimum inplementation of a rust cloudflare worker.  
I made this to learn and try out cloudflare workers.

### Built With

* [Rust](https://www.rust-lang.org/tools/install)
* [Cloudflare workers](https://workers.cloudflare.com/)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.


### Prerequisites

* [Rust](https://www.rust-lang.org/tools/install)
* [Wrangler](https://developers.cloudflare.com/workers/cli-wrangler/install-update)

### Installation

#### Cloning


1. Clone the repo
   ```sh
   git clone https://github.com/BrammyS/rust-wasm-worker.git
   ```
2. Go to the git folder
   ```sh
   cd rust-wasm-worker
   ```
3. Run the local dev build
   ```sh
   wrangler dev
   ```



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the Apache License 2.0 License. See `LICENSE` for more information.



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Chrono](https://docs.rs/chrono/latest/chrono/)
* [cfg-if](https://docs.rs/cfg-if/latest/cfg_if/)
* [Worker](https://docs.rs/worker/latest/worker//)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[stars-shield]: https://img.shields.io/github/stars/BrammyS/rust-wasm-worker.svg?style=for-the-badge
[stars-url]: https://github.com/BrammyS/rust-wasm-worker/stargazers
[issues-shield]: https://img.shields.io/github/issues/BrammyS/rust-wasm-worker.svg?style=for-the-badge
[issues-url]: https://github.com/BrammyS/rust-wasm-worker/issues
[license-shield]: https://img.shields.io/github/license/BrammyS/rust-wasm-worker.svg?style=for-the-badge
[license-url]: https://github.com/BrammyS/rust-wasm-worker/blob/master/LICENSE.txt
