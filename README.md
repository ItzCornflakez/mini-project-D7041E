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
  <a href="https://github.com/ItzCornflakez/mini-project-D7041E">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Fake Review Classification With Fokus On Vector Representations</h3>

  <p align="center">
   <!-- project_description -->
    <br />
    <a href="https://github.com/ItzCornflakez/mini-project-D7041E"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ItzCornflakez/mini-project-D7041E">View Demo INSERT YOUTUBE LINK</a>
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
This projekt is about classifying fake product reviews using different classifiers to figure out how well fake reviews can be detected and which classifier gets the best results


### Classifiers
The classifiers we have fokused on are Random Forest, AdaBoost, KNN, LinReg, SVM and MLP


### Preprocessing
For preprocessing we did tokenization, stopword removal, special character removal and lemmatization returning the text as lowercase. We do this to remove unuseful parts of the text that would not be helpful for classifying it.


### Getting the optimal parameters
To get the optimal parameters we utilised k-folding (k=3) on a validation set of 8% of the entire dataset (3234 rows)


[![Product Name Screen Shot][product-screenshot]](https://example.com)

<!-- Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `ItzCornflakez`, `mini-project-D7041E`,  `Fake Review Classification With Fokus On Vector Representations`, `project_description` -->

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [JupyterLab](https://jupyter.org/)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

This projekt was built on windows using Anaconda which can be acquired on https://www.anaconda.com/products/distribution

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

in addition to anaconda som additional librarys need to be installed such as
* pip
  ```sh
  pip install sklearn
  ```
  ```sh
  pip install pandas
  ```
  ```sh
  pip install nltk
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ItzCornflakez/mini-project-D7041E.git
   ```
2. Install librarys
   ```sh
   pip install sklearn
   ```
   ```sh
   pip install pandas
   ```
   ```sh
   pip install nltk
   ```
3. Run code using prefered JupyterLab code editor

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

## Results
The results for the different classifiers are as follows

### Text based approach

![alt text](https://github.com/ItzCornflakez/mini-project-D7041E/blob/master/images/text_based_accuracy.png?raw=true)

### Text and feature based approach

### Random Forest
#### Text based approach
* with TF-IDF

* with Bag-of-words

#### Text and feature based approach
* with TF-IDF

* with Bag-of-words


### AdaBoost
#### Text based approach
* with TF-IDF

* with Bag-of-words

#### Text and feature based approach
* with TF-IDF

* with Bag-of-words


### KNN 
#### Text based approach
* with TF-IDF

* with Bag-of-words

#### Text and feature based approach
* with TF-IDF

* with Bag-of-words


### LinReg
#### Text based approach
* with TF-IDF

* with Bag-of-words

#### Text and feature based approach
* with TF-IDF

* with Bag-of-words


### SVM 
#### Text based approach
* with TF-IDF

* with Bag-of-words

#### Text and feature based approach
* with TF-IDF

* with Bag-of-words


### MLP
#### Text based approach
* with TF-IDF

* with Bag-of-words

#### Text and feature based approach
* with TF-IDF

* with Bag-of-words


<p align="right">(<a href="#top">back to top</a>)</p>


## Conclusions

### Best Classifier and Models

We found that from our tests the XXXXX model generally gave the best accuracy and the XXXXX classifier gave the overall highest accuracy

_For additional explanations and findings, please refer to youtube video [Documentation](https://example.com)_ (Insert link to youtube video)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Alexander Österberg - aleste-9@student.ltu.se

Pontus Schünemann - ponsch-9@student.ltu.se

Emil Nyberg - eminyb-9@student.ltu.se


Project Link: [https://github.com/ItzCornflakez/mini-project-D7041E](https://github.com/ItzCornflakez/mini-project-D7041E)

Youtube Link: [https://YoutubeLink](https://youtubeLink)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Fake reviews dataset from OSFHOME: [Fake Reviews Dataset](https://osf.io/tyue9/)
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ItzCornflakez/mini-project-D7041E.svg?style=for-the-badge
[contributors-url]: https://github.com/ItzCornflakez/mini-project-D7041E/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ItzCornflakez/mini-project-D7041E.svg?style=for-the-badge
[forks-url]: https://github.com/ItzCornflakez/mini-project-D7041E/network/members
[stars-shield]: https://img.shields.io/github/stars/ItzCornflakez/mini-project-D7041E.svg?style=for-the-badge
[stars-url]: https://github.com/ItzCornflakez/mini-project-D7041E/stargazers
[issues-shield]: https://img.shields.io/github/issues/ItzCornflakez/mini-project-D7041E.svg?style=for-the-badge
[issues-url]: https://github.com/ItzCornflakez/mini-project-D7041E/issues
[license-shield]: https://img.shields.io/github/license/ItzCornflakez/mini-project-D7041E.svg?style=for-the-badge
[license-url]: https://github.com/ItzCornflakez/mini-project-D7041E/blob/master/LICENSE.txt
[product-screenshot]: images/screenshot.png
