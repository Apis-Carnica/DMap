<div id="top"></div>
<!-- PROJECT SHIELDS -->
![[Read the Docs](https://img.shields.io/readthedocs/dmap)](https://dmap.readthedocs.io/en/)
![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/nateac1/DMap)
![Discord](https://img.shields.io/discord/977772351519342592)
![Website](https://img.shields.io/website?down_color=red&down_message=down&up_color=green&up_message=up&url=https%3A%2F%2Fdmap.org)
![PyPI - Status](https://img.shields.io/pypi/status/DMap)


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/nateac1/DMap">
    <img src="https://cdn.discordapp.com/attachments/454864152486477825/977801099912286238/IMG_5667.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">DMap</h3>

  <p align="center">
    Nmap integrated in Discord for ease of scanning.
    <br />
    <a href="https://dmap.readthedocs.io/en/latest/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/nateac1/DMap/releases">Get the code</a>
    ·
    <a href="https://github.com/nateac1/DMap/issues">Report Bug</a>
    ·
    <a href="https://github.com/nateac1/DMap/issues">Request Feature</a>
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
        <li><a href="#prerequisites">Words of Warning</a></li>
        <li><a href="#installation">Installation & Setup</a></li>
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

![dmap-screenshot](https://cdn.discordapp.com/attachments/454864152486477825/977821349877809192/Screenshot_20220521-222728_Discord.png)

Whether I'm working on HackTheBox challenges, or require a convenient way to scan a domain while I'm on the road, I always have access to Discord. The PoC of this project was started a few years ago, and this time a full-fledged environment will be available to all who need it. DMap intends to offer a convenient environment for scanning over a VPN connection, such as HackTheBox, remote enterprise, or CTF connections. Some functionality for creating a VPN connection to the device in order to scan local networks is in the works, but may be a bit delayed.

Why use DMap:
* Hands-on examples are more effective in teaching environments like school clubs, where students can follow along with a presenter in chat
* Simple scans can be handled in a few seconds from a mobile device or in any browser without requiring you to boot up your hacking machine
* Utilize MAC changing, IP rotation, and a sandboxed environment without effort

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

Obviously, the two major components this project utilizes are Nmap and Discord's API. A few different modules and frameworks will also be included to handle VPN connections, different kinds of scanning and recon actions, and other security-related functions; this list will grow as the program does.

* [Nmap](https://nmap.org/)
* [Discord's Python API](https://discordpy.readthedocs.io/en/stable/api.html)
* [OpenVPN](https://openvpn.net/)
* [PwnTools](https://docs.pwntools.com/en/stable/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Words of Warning

If you plan on only using this solution in another person's server, feel free to skip this bit. If you'd like to host a free-running server for your own use, please heed the following advice. **Host this solution in a sandboxed environment, or on a machine/network that you have no personal stake in**. I cannot stress operational security enough in an environment where there are built-in security vulnerabilities; please use this software at your own discretion (and don't sue me if someone manages to run `os.system("rm -rf /")` on your un-hardened machine).


### Installation & Setup

When I automate the setup process, I'll add further instruction for installation and setup. For now, you'll just have to work it out on your own or use this on a Discord server.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

This space will be filled with examples of usage as the application is built and tested. For now, I appreciate your patience and look forward to making scanning easier for you in the near future!
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [ ] Recreate basic functionality
    - [ ] Simple Nmap scans over the public internet
    - [ ] Simple scans over VPN
    - [ ] Session and scan hosting for later reference
- [ ] Automate the setup of the server
- [ ] Add various scanning options to the application
- [ ] Plan additional features
- [ ] Multi-language Support
    - [ ] Japanese
    - [ ] German
    - [ ] French
    - [ ] Spanish
    - [ ] TBD

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for any proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the GPLv3 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Nathan Christensen - [HTB Profile](https://app.hackthebox.com/profile/145078) - ursa@artiotech.org

Project Link: [https://github.com/nateac1/DMap](https://github.com/nateac1/DMap)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#top">back to top</a>)</p>
