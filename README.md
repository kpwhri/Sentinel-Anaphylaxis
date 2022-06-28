

<div>
  <p>
    <a href="https://github.com/kpwhri/Sentinel-Anaphylaxis">
      <!-- img src="images/logo.png" alt="Logo" -->
    </a>
  </p>

  <h3 align="center">Sentinel Anaphylaxis</h3>

  <p>
    Detecting Anaphylaxis from structured and unstructured medical data.
  </p>
</div>


## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project



<!-- GETTING STARTED -->
## Getting Started

The project is divided into several steps/stages:

0. Structured Data Variables (SAS)
  * Build variables from structured data
  * [Instructions](0-Structured-Data/README.md)
1. NLP Variables (Python)
  * Build variables from unstructured data (i.e., EHR text)
  * [Instructions](1-NLP-Data/README.md)
2. Merging NLP/Structured Data (SAS)
  * Merge data from 0 and 1, and then prepare/clean for building model
  * [Instructions](2-Merging-Data/README.md)
3. Building a Model (R)
  * Building prediction algorithm
  * [Instructions](3-Building-Model/README.md)

### Prerequisites

* Python 3.8+
* SAS version 9.4+ (?)
* Data model (which data model?)
* R version ?


<!-- USAGE EXAMPLES -->
## Usage

0. [Build structured data variables](0-Structured-Data/README.md)
1. [Build NLP data variables](1-NLP-Data/README.md)
2. [Merge structured and NLP variables and prepare for model building](2-Merging-Data/README.md)
3. [Build model from structured and unstructured variables](3-Building-Model/README.md)



## Versions

<!-- Uses [SEMVER](https://semver.org/). -->

Updates/changes are not expected. Versioning likely based on release timing in `YYYYmm`. See https://github.com/kpwhri/Sentinel-Anaphylaxis/releases.


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/kpwhri/Sentinel-Anaphylaxis/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` or https://kpwhri.mit-license.org for more information.



<!-- CONTACT -->
## Contact

Please use the [issue tracker](https://github.com/kpwhri/Sentinel-Anaphylaxis/issues). 


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* This work was funded as part of the [Sentinel Initiative](https://www.fda.gov/safety/fdas-sentinel-initiative).

