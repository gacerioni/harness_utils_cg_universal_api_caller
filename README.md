
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/gacerioni/harness_utils_cg_universal_api_caller">
    <img src="images/harness_banner.jpeg" alt="Logo">
  </a>

  <h3 align="center">Harness CD Current-Gen Universal API Caller - by Gabs the CSE</h3>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation-and-usage">Installation and Usage</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#tech-stack">Tech Stack</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The main goal of this project is to mantain a trustful source of Python calling Harness APIs. This initial project will evolve to support all RESTful Methods.
For now, this is a Project to call DELETE and help with a specific Customer use case.


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* [python3.6+](https://www.python.org/downloads/)

* A Harness account, of course!

* For MacOs Users, please double-check the SSL CERT
   ```sh
   cd /Applications/Python\ 3.9/ # PUT YOUR PYTHON VERSION
   ./Install\ Certificates.command
   ```

### Installation and Usage

1. Clone the repo
   ```sh
   git clone https://github.com/gacerioni/harness_instanceStats_gql_to_csv.git
   cd harness_instanceStats_gql_to_csv
   ```
2. Install the project dependecies (very simple stuff, meant to deal with requests, json, html)
   ```sh
   pip install -r requirements.txt
   <OR>
   python3 -m pip install -r requirements.txt
   ```
3. Export the required variables (Just to avoid Secrets, KMS, Vaults, etc, to keep this project simple)
   ```sh
   python(3) main.py -h
   ```

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/gacerioni/harness_utils_cg_universal_api_caller/issues) for a list of proposed features (and known issues).



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

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Gabriel Cerioni - [@gabs.tar.gz](https://www.instagram.com/gabs.tar.gz/) - gacerioni@gmail.com

Project Link: [https://github.com/gacerioni/harness_utils_cg_universal_api_caller/](https://github.com/gacerioni/harness_utils_cg_universal_api_caller/)

<!-- Tech Stack -->
## Tech Stack

* [Python](https://www.python.org/)
* [Harness](https://harness.io)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/gacerioni/harness_utils_cg_universal_api_caller.svg?style=for-the-badge
[contributors-url]: https://github.com/gacerioni/harness_utils_cg_universal_api_caller/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/gacerioni/harness_utils_cg_universal_api_caller.svg?style=for-the-badge
[forks-url]: https://github.com/gacerioni/harness_utils_cg_universal_api_caller/network/members
[stars-shield]: https://img.shields.io/github/stars/gacerioni/harness_utils_cg_universal_api_caller.svg?style=for-the-badge
[stars-url]: https://github.com/gacerioni/harness_utils_cg_universal_api_caller/stargazers
[issues-shield]: https://img.shields.io/github/issues/gacerioni/harness_utils_cg_universal_api_caller.svg?style=for-the-badge
[issues-url]: https://github.com/gacerioni/harness_utils_cg_universal_api_caller/issues
[license-shield]: https://img.shields.io/github/license/gacerioni/harness_utils_cg_universal_api_caller.svg?style=for-the-badge
[license-url]: https://github.com/gacerioni/harness_utils_cg_universal_api_caller/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/gacerioni
