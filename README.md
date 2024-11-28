<div align="center">
  <p>
    <a href="https://icaerus.eu" target="_blank">
      <img width="50%" src="https://icaerus.eu/wp-content/uploads/2022/09/ICAERUS-logo-white.svg"></a>
    <h3 align="center">ICAERUS GitHub repo template🦚</h3>
    
   <p align="center">
    Template to copy-paste or take as an example for other ICAERUS GitHub repo's, orginating from WP2.
    <br/>
    <br/>
    <br/>
    <br/>
    <a href="https://github.com/icaerus-eu/icaerus-repo-template/issues">Report Bug</a>
    -
    <a href="https://github.com/icaerus-eu/icaerus-repo-template/issues">Request Feature</a>
  </p>
</p>
</div>

![Downloads](https://img.shields.io/github/downloads/icaerus-eu/icaerus-repo-template/total) ![Contributors](https://img.shields.io/github/contributors/icaerus-eu/icaerus-repo-template?color=dark-green) ![Forks](https://img.shields.io/github/forks/icaerus-eu/icaerus-repo-template?style=social) ![Stargazers](https://img.shields.io/github/stars/icaerus-eu/icaerus-repo-template?style=social) ![Issues](https://img.shields.io/github/issues/icaerus-eu/icaerus-repo-template) ![License](https://img.shields.io/github/license/icaerus-eu/icaerus-repo-template) 

## Table Of Contents

* [Summary](#summary)
* [Readme requirements](#readme-requirements)
* [Repo requirements](#repo-requirements)
* [Authors](#authors)
* [Acknowledgments](#acknowledgments)
  
## Summary
This GitHub repository template is designed for the ICAERUS-EU project, providing a standardized structure for managing and sharing project-related code, documentation, and resources. It includes essential folders and files to help streamline development, collaboration, and tracking progress within the project.

## Readme requirements
The idea is that this readme text is copied and adjusted for your own project-repo readme. 
Start by [creating a repo on GitHub](https://docs.github.com/en/get-started/quickstart/create-a-repo), from your GitHub account. 

### Header
You can copy-and-paste the header and shields directly into your own readme file (please change the `repo-title` in the urls to the correct ones).
```markdown
<div align="center">
  <p>
    <a href="https://icaerus.eu" target="_blank">
      <img width="50%" src="https://icaerus.eu/wp-content/uploads/2022/09/ICAERUS-logo-white.svg"></a>
    <h3 align="center">TITLE OF YOUR REPO/PROJECT🦚</h3>
    
   <p align="center">
    Short description of the content/subject matter in the repository
    <br/>
    <br/>
    <a href="https://github.com/icaerus-eu/repo-title/wiki"><strong>Explore the wiki »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/icaerus-eu/repo-title/issues">Report Bug</a>
    -
    <a href="https://github.com/icaerus-eu/repo-title/issues">Request Feature</a>
  </p>
</p>
</div>

![Downloads](https://img.shields.io/github/downloads/icaerus-eu/repo-title/total) ![Contributors](https://img.shields.io/github/contributors/icaerus-eu/repo-title?color=dark-green) ![Forks](https://img.shields.io/github/forks/icaerus-eu/repo-titlee?style=social) ![Stargazers](https://img.shields.io/github/stars/icaerus-eu/repo-title?style=social) ![Issues](https://img.shields.io/github/issues/icaerus-eu/repo-title) ![License](https://img.shields.io/github/license/icaerus-eu/repo-title) 
```
### Table of contents
We also expect a Table of Contents directly after the header, with linked section like the one in this repo, some ideas for sections are given below. 
```markdown
## Table Of Contents
- [Summary](#summary)
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Development](#development)
- [Testing](#testing)
- [Documentation](#documentation)
- [License](#license)
- [Support](#support)
- [Security](#security)
- [Acknowledgments](#acknowledgments)
- [Resources](#resources)
- [FAQ](#faq)
- [Gallery](#gallery)
- [Deployment](#deployment)
- [Demo](#demo)
- [Dependencies](#dependencies)
- [Known Issues](#known-issues)
- [Roadmap](#roadmap)
```

Please include the `Acknowledgments` section  with EU-funding acknowledments.

```markdown
## Acknowledgements
This project is funded by the European Union, grant ID 101060643.

<img src="https://rea.ec.europa.eu/sites/default/files/styles/oe_theme_medium_no_crop/public/2021-04/EN-Funded%20by%20the%20EU-POS.jpg" alt="https://cordis.europa.eu/project/id/101060643" width="200"/>

```
### ICAERUS organization
You can decide later or immediately to publish it under the ICAERUS organization (if you are already a member). **If your are not a member yet of this organization, please send an e-mail to [jurrian.doornbos@wur.nl](mailto:jurrian.doornbos@wur.nl?subject=ICAERUS-Github-access) with your GitHub account information: email/username.**

You can change it to the ICAERUS organization also [later down the line](https://docs.github.com/en/repositories/creating-and-managing-repositories/transferring-a-repository) if you are not immediatly ready yet. Make sure to change all the URLs in the headers, image, etc. to reflect this transfer: `https://github.com/jurriandoornbos/uavgeo` -> **`https://github.com/icaerus-eu/uavgeo`**


## Repo requirements
### License
The Drone Data Analytics Library is open source, allowing anyone to view, modify, and contribute to its development. Contributors have the flexibility to choose from several open-source licenses as defined by the Open Source Initiative (OSI). You can explore these options at [OSI's official site](https://opensource.org/licenses).

Some popular open-source licenses allowed in the DDAL:
 - CC-BY: Creative Commons Attribution license, allowing use and modification as long as proper credit is given.
 - Apache 2.0: A permissive license that provides an express grant of patent rights to users and requires attribution.
 - MIT: A simple and permissive license, allowing reuse with minimal restrictions, only requiring attribution.
 - GPLv3: A copyleft license that ensures any derivative work must also be open source under the same license.

### Folder structure
From there on in, you can decide on folder structure which makes the most sense for the project. For some ideas of folder structures you can do [some research](https://mitcommlab.mit.edu/broad/commkit/file-structure/), or use what is already logical to you/your organization.
```
Ideas:
- .github/                   # GitHub-specific files and templates
  - workflows/               # Workflow configuration files (e.g., CI/CD)
- docs/                      # Documentation files (e.g., user guides)
- src/                       # Source code for your project
- tests/                     # Test files
- data/                      # Data files (if applicable)
- config/                    # Configuration files
- scripts/                   # Utility scripts
- public/                    # Publicly accessible assets (e.g., web assets)
- dist/                      # Compiled or distribution files
- examples/                  # Example code or usage examples
- LICENSE                    # Your project's license file
- README.md                  # Repository README
```

You can also check out [`uavgeo`](https://github.com/icaerus-eu/uavgeo) for an example `python` project folder/file structure that is published and available through `pip`. Or [`p2p-ros`](https://github.com/jurriandoornbos/p2p_ros) for a ROS related project.

### ICAERUS Platform integration

To help out findability, and usability in the ICAERUS platform (WP6), the repo's should include a `platform.json`, following the template included in [Icaerus_Template](https://github.com/ICAERUS-EU/icaerus-repo-template/blob/main/platform.json). Then fill in the required information of your model to the file in your repo. In this template, you should also add the url for the specific model folder and the image reference of the performance expected. You can look at the example [UC1 PLATFORM JSON](https://github.com/ICAERUS-EU/UC1_Crop_Monitoring/blob/main/platform.json). 

This information will be used to upload the [ICAERUS PLATFORM](https://www.platform.icaerus.eu/) so its implementation it's extremely important. As every UC uploads their models and updates the `platform.json`, we will monthly translate this information to the main `platform.json` located in the [ICAERUS_DDAL](https://github.com/ICAERUS-EU/ICAERUS_DDAL/tree/main) that is the one used for the integration with the platform. 

Additionally, the platform.json serves to structure metadata about the model for findability and accessibility wihtin the platforms.


## Authors

* **Jurrian Doornbos** - *Wageningen University* - [Jurrian Doornbos](https://github.com/jurriandoornbos)

## Acknowledgements
This project is funded by the European Union, grant ID 101060643.

<img src="https://rea.ec.europa.eu/sites/default/files/styles/oe_theme_medium_no_crop/public/2021-04/EN-Funded%20by%20the%20EU-POS.jpg" alt="https://cordis.europa.eu/project/id/101060643" width="200"/>
