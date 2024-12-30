# Exploring-plasticity-of-the-tomato-seed-microbiome
Here, bacterial amplicon sequencing analyses of so far largest microbiome dataset involving 100 tomato cultivars were conducted to examine plant genetics and environmental factors influencing the seed microbiome composition.

# Project Name

**Project Description:**  
A brief description of what your project does and its purpose.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Prerequisites](#prerequisites)
4. [Dependencies](#dependencies)
5. [Contributing](#contributing)
6. [License](#license)

## Installation

**Step-by-step instructions on how to install the project:**

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```sh
    cd your-repo-name
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```
    or
    ```sh
    pip install -r requirements.txt
    ```

## Usage

**Instructions on how to use the project:**

1. Run the application:
    ```sh
    npm start
    ```
    or
    ```sh
    python main.py
    ```
2. Access the application via [http://localhost:3000](http://localhost:3000) or your specified port.

## Prerequisites

**List any prerequisites for the project:**

- Node.js v14 or higher
- Python 3.8 or higher
- Any other software or tools required

## Dependencies

**List any dependencies required by the project:**

- express: ^4.17.1
- react: ^17.0.2
- flask: ^2.0.1
- Any other libraries or modules

## Contributing

**Guidelines for contributing to the project:**

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-foo`).
3. Make your changes and commit them (`git commit -m 'Add some foo'`).
4. Push to the branch (`git push origin feature-foo`).
5. Create a new Pull Request.

## License

**Specify the license under which the project is released:**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


setwd("/Users/expeditoolimi/Documents/Southampton/Global_tomato_seed_Microbiome/Tomato100_Project")
library(phyloseq);packageVersion("phyloseq")#‘1.46.0’
library(vegan);packageVersion("vegan")# ‘2.6.4’
library(genefilter);packageVersion("genefilter")#‘1.84.0’
library(psych);packageVersion("psych")#‘2.4.1’
library(DESeq2);packageVersion("DESeq2")#‘1.42.1’
library(ggplot2);packageVersion("ggplot2")#‘3.5.0’
library(reshape2);packageVersion("reshape2")#‘1.4.4’
library(microbiome);packageVersion("microbiome")#‘1.24.0’
library(ranacapa);packageVersion("ranacapa")#‘0.1.0’
library(S4Vectors);packageVersion("S4Vectors")#‘0.40.2’
library(Biobase);packageVersion("Biobase")#‘2.62.0’
library(BiocGenerics);packageVersion("BiocGenerics")#‘0.48.1’
library(parallel);packageVersion("parallel")#‘4.3.2’
library(ggpubr);packageVersion("ggpubr")#‘0.6.0’
