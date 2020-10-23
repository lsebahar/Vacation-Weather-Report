<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email
-->





<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/lsebahar/Vacation-Weather-Report-Generator">
    <img src="Images/beach-image.jpg" alt="Logo" width="1000" height="300">
  </a>

  <h3 align="center">Vacation Weather Checker</h3>

  <p align="center">
    Leveraging API's to help you prepare for your vacation!
    <br />
    <a href="https://github.com/lsebahar/Vacation-Weather-Report-Generator"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/lsebahar/Vacation-Weather-Report-Generator">View Demo</a>
    ·
    <a href="https://github.com/lsebahar/Vacation-Weather-Report-Generator/issues">Report Bug</a>
    ·
    <a href="https://github.com/lsebahar/Vacation-Weather-Report-Generator/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project


Netflix binges have become, for better or worse, part of American culture. With movies chock-full of data, we got an idea--are these unintentional all-day viewing parties-of-one just as random as what catches the viewer's attention? What kind of interesting trends do people have in their viewing history? 

We set out to create an ETL process to empower a user to query stats and discern trends. The general process is relatively simple. Download viewing history data from Netflix. Clean that data, then use the titles to pull data related to cast, genre, etc from the Open Movie Database. Load all of this data to PostgreSQL, then presto: you have the ability to query from a relational database. 


### Built With

* Jupyter Notebook
* Python
* JSON
* Gmaps



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

1) Install gmaps and obtain an API key

2) Install citipy

3) Install Pandas, numpy, matplotlib, scipy

4) Install Jupyter Notebook


### Installation

1) Clone the repo
```sh
git clone https://github.com/lsebahar/Vacation-Weather-Report-Generator.git
```


2) Add to the "Code" folder a config.py file which contains the variable api_key (for your gmaps key) as well as the connection string to your postgreSQL application. 
<img src="Images/config_image.png" alt="Logo" width="100" height="100">

```sh
api_key = 'apikeyhere'
```


3) Add your CSV files to the "Netflix_Data" folder, and align with the code in "Code/ETL-Script.ipynb" (e.g. "User1.csv")

4) Run the Jupyter Notebook cells 


<!-- USAGE EXAMPLES -->
## Usage

Now you can query using SQL! 

<img src="Images/Latitude_vs_Temp_northhemi.png" alt="Logo" width="200" height="200">



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/lsebahar/Vacation-Weather-Report-Generator/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- CONTACT -->
## Contact

Levi Sebahar - leviseb@gmail.com

Project Link: [https://github.com/lsebahar/Vacation-Weather-Report-Generator](https://github.com/lsebahar/Vacation-Weather-Report-Generator)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* The Data Science & Visualization Bootcamp
* UCSD Extension
* Github user othneildrew (readme template)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=flat-square
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=flat-square
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=flat-square
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=flat-square
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=flat-square
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
[product-screenshot]: images/screenshot.png
