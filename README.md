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
   <!-- <img src="images/logo.png" alt="Logo" width="80" height="80"> -->
  </a>

<h3 align="center">Fake Review Classification With Focus On Vector Representations</h3>

  <p align="center">
   <!-- project_description -->
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
This project was made for the D7041E course at LTU taken at winter 2022. This project aims to use a handfull of different classifiers in order to classify fake reviews. Our main focus was to compare the performances you get when using TF-IDF and Bag of Words text embedding techniques.   

### Classifiers
The classifiers we have focused on are Random Forest, AdaBoost, KNN, SVM and MLP


### Preprocessing
For preprocessing we did tokenization, stopword removal, special character removal and lemmatization returning the text as lowercase. We do this to remove unuseful parts of the text that would not be helpful for classifying it.


### Getting the optimal parameters
To get the optimal parameters we utilised k-folding (k=3) on a validation set of 8% of the entire dataset (3234 rows)


<!-- Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `ItzCornflakez`, `mini-project-D7041E`,  `Fake Review Classification With Focus On Word Embedding techniques`, `project_description` -->

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Jupyter Notebook](https://jupyter.org/)


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

![alt text](https://github.com/ItzCornflakez/mini-project-D7041E/blob/master/images/mini_project_Result_textBased_Updated.PNG?raw=true) 
<br />
In the above image the best classifiers was SVM. It produced a better accuracy using the word embedding technique TF-IDF, as did most of the other classifiers. From this we concluded that TF-IDF was a more suited technique for this than BagOfWords.
<br />
<br />
### Text based approach with voting
![alt text](https://github.com/ItzCornflakez/mini-project-D7041E/blob/master/images/mini_project_Result_textBased_vote_BagOfWords.PNG?raw=true) 
<br />
Above is bag of words classification with voting.
<br />
<br />
![alt text](https://github.com/ItzCornflakez/mini-project-D7041E/blob/master/images/mini_project_Result_textBased_vote_TFIDF.PNG?raw=true) 
<br />
Above is TF-IDF classification with voting.
<br />
Apart from the fact that the TF-IDF word embedding technique gave a better accuracy overall in the above results, the other classifers apart from SVM gave such a bad accuracy they pulled down the overall accuracy in the voting process. This also applied when doing the vote for the 3 different features.  
<br />

<p align="right">(<a href="#top">back to top</a>)</p>


## Conclusions
Our findings from this mini-project suggest that using the TF-IDF word embedding technique typically leads to better classification accuracy. Additionally, we found that using other features in combination with the preprocessed text, through majority voting, often results in lower accuracy compared to using only the preprocessed text. This is due to the low classification accuracy of the other features, meaning that they are not good at classifying reviews correctly.  The best results were obtained using an SVM classifier on the preprocessed text alone, resulting in an accuracy of around 89%. This indicates that this method can be an effective way to classify reviews for this particular dataset. However, it is important to note that the results of this mini-project may not be applicable to other datasets or classification tasks, and further evaluation may be necessary before using this method in a commercial setting.
### Best Classifier and Models

We found that from our tests the text based model generally gave the best accuracy and the SVM classifier gave the overall highest accuracy.

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
## Dataset

* Fake reviews dataset from OSFHOME: [Fake Reviews Dataset](https://osf.io/tyue9/)

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
