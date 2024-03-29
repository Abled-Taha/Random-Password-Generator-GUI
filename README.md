[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<h1 align="center">(Depricated)</h1>
<h6 align="center">New Version: https://github.com/Abled-Taha/UPM</h6>
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="src/Files/icon.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Random-Password-Generator</h3>

  <p align="center">
    An awesome application to randomly generate your passwords and manage them!
    <br />
    ·
    <a href="https://github.com/Abled-Taha/Random-Password-Generator-GUI/issues">Report Bug</a>
    ·
    <a href="https://github.com/Abled-Taha/Random-Password-Generator-GUI/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#features">Features</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <ul>
        <li><a href="#windows-installation">Windows Installation</a></li>
        </ul>
        <li><a href="#building">Building</a></li>
        <ul>
        <li><a href="#windows-building">Windows Building</a></li>
        </ul>
        <ul>
        <li><a href="#linux-building">Linux Building</a></li>
        </ul>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

There are many great Password Managers available out-there having more features than this application and I even recommend using those ones as your main Password Manager, however, I just started this project as a hobby and I am working on it so, if you want to try it, you are more than welcome to.

### Features:
* Account Creation
* Account Logging In
* Password Verification In Creation and Logging
* Random Password Generation
* Creation and Deletion of Generated Passwords
* Encryption of Passwords before storing
* One Master Password to protect all passwords

### Built With

* [PyQt5](https://pypi.org/project/PyQt5/)


<!-- GETTING STARTED -->
## Getting Started

This project is supported to Windows and Linux, however, for Windows I do have official releases but as for Linux there are no releases, you have to build it yourself. Moreover, The releases are only for the main branch of the project if you want to try another branch, you need to build it yourself.

### Installation

#### Windows Installation

1. Download the installer from <a href='https://github.com/Abled-Taha/Random-Password-Generator-GUI/releases/tag/v.2.0'>here</a> and proceed from there.

### Building
#### Windows Building
1. Open CMD and change to your desired directory
2. Clone this repository
   ```sh
   git clone https://github.com/Abled-Taha/Random-Password-Generator-GUI
   ```
3. Change directory
   ```sh
   cd Random-Password-Generator-GUI
   ```
4. Install required packages
   ```sh
   pip install -r requirements.txt
   ```
5. Build the App
   ```sh
   pyinstaller "Random Password Generator.spec"
   ```
6. Move the directory "Random Password Generator" located under "dist" directory to your desired location. (It is your application directory.)
7. Find the "Random Password Generator.exe" file in the application directory and make it's shortcut to your Desktop or somewhere.

#### Linux Building
1. Open Terminal and change to your desired directory
2. Clone this repository
   ```sh
   git clone https://github.com/Abled-Taha/Random-Password-Generator-GUI
   ```
3. Change directory
   ```sh
   cd Random-Password-Generator-GUI
   ```
4. Install required packages
   ```sh
   pip3 install -r requirements.txt
   ```
5. Build the App
   ```sh
   pyinstaller "Random Password Generator.spec"
   ```
6. Move the directory "Random Password Generator" located under "dist" directory to your desired location. (It is your application directory.)
7. Find the "Random Password Generator" file in the application directory which is the main file to execute.


<!-- USAGE EXAMPLES -->
## Usage

This product should only be used as an **exploration or educational** project and is not recommended to be used as a primary Password Manager as it lacks many essential features like, storing your password and user accounts in database, rather it stores all the data on your **local machine**.

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Abled-Taha/Random-Password-Generator-GUI/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

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

Abled Taha - [@AbledTaha](https://twitter.com/@AbledTaha) - abledtaha@gmail.com

Project Link: [https://github.com/Abled-Taha/Random-Password-Generator-GUI](https://github.com/Abled-Taha/Random-Password-Generator-GUI)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Abled-Taha/Random-Password-Generator-GUI.svg?style=for-the-badge
[contributors-url]: https://github.com/Abled-Taha/Random-Password-Generator-GUI/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Abled-Taha/Random-Password-Generator-GUI.svg?style=for-the-badge
[forks-url]: https://github.com/Abled-Taha/Random-Password-Generator-GUI/network/members
[stars-shield]: https://img.shields.io/github/stars/Abled-Taha/Random-Password-Generator-GUI.svg?style=for-the-badge
[stars-url]: https://github.com/Abled-Taha/Random-Password-Generator-GUI/stargazers
[issues-shield]: https://img.shields.io/github/issues/Abled-Taha/Random-Password-Generator-GUI.svg?style=for-the-badge
[issues-url]: https://github.com/Abled-Taha/Random-Password-Generator-GUI/issues
[license-shield]: https://img.shields.io/github/license/Abled-Taha/Random-Password-Generator-GUI.svg?style=for-the-badge
[license-url]: https://github.com/Abled-Taha/Random-Password-Generator-GUI/blob/main/LICENSE.txt
