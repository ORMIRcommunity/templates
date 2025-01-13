# [ORMIR community](https://ormircommunity.github.io/) template for the README.md file in a GitHub repository

by [Serena Bonaretti](https://sbonaretti.github.io/), [Donnie Cameron](https://www.linkedin.com/in/donnie-cameron-b76bbb63/?originalSubdomain=uk),  [Michelle Alejandra Espinosa Hernandez](https://www.linkedin.com/in/michelleaespinosah/), [Gianluca Iori](https://github.com/gianthk), 2023  
Version 1.0


- *In the following, you will find suggestions on how to structure the `README.md` file of your GitHub repository*
- *Instructions are in italics, and you can delete them when using this template*
- *Feel free to add figures and videos illustrating your package in any section*  
- *You can find some examples of `README.md` using the ORMIR `README.md` template in the repositories of these packages*:
  - [ORMIR-MIDS](https://github.com/ormir-mids/ormir-mids/blob/main/README.md)  
  - [Ciclope](https://github.com/ciclope-microFE/ciclope/blob/master/README.md)    
- *Delete this and the lines above when releasing your own `README.md`*

---
---



# Package_name

- *Add badges here. Recommended badges are*:
  - [Doc badges](https://docs.readthedocs.io/en/stable/badges.html)  
  - [CodCov](hhttps://about.codecov.io/) 
  - [License](https://shields.io/category/license)
  - [Package version](https://shields.io/category/platform-support)
  - [Python version](https://shields.io/category/platform-support) 
- *Add a few lines describing of the package* 
- *Add a table of content (TOC) if relevant (see how to create a TOC in markdown/html in [Appendix 1 of the ORMIR notebook template](https://github.com/ORMIRcommunity/templates/blob/main/ORMIR_nb_template.ipynb))*


---
## Installation

- *Specify how to install your package, such as:*

  > Install [package_name] by pasting the following line in a terminal:   
  > `pip install package_name`

- *If you install from Anaconda*:
   > Install [package_name] by pasting the following line in a terminal:   
   > `conda install package_name`


### Development installation 
- *If you want to contribute, start by cloning the repository*:     
    > `!git clone https://github.com/[account_name]/[package_name].git`  
- *Navigate to repo folder*:
    > `%cd [package_name]`  
    
- *Install using pip*:
    > `!pip install .`
  

--- 
## Usage 

- *A Python package can be imported in Python code and/or run from a command line as a script.*
- *If you package is imported in Python code, add something like:*  

  > To use [package_name] in your code, import it as:  
  > `import package_name`
- *If you package can be run from command line, add something like:*   
  
  > To run [package_name] from terminal, type:   
  >`package_name parameter1 parameter2`


--- 
## Documentation / User guide / Tutorials

*Please, take particular care of documentation and examples, so that other researchers can easily use your code*
- *For the documentation:*
  - *Indicate if the project has a website (see an example of a website created with Jupyter Book [here](https://ormir-mids.github.io/))*
- *You can write the examples*:
  - *Directly here in the readme file (see example [here](https://github.com/gianthk/ciclope))*  
  - *In Jupyter notebooks (see example [here](https://github.com/ormir-mids/ormir-mids/blob/main/README.md)). In this case, add links to [binder](https://mybinder.org/) whenever possible (learn how to link your GitHub repository to Binder, by reading this [documentation](https://mybinder.readthedocs.io/en/latest/introduction.html) or watching [this video](https://www.youtube.com/watch?v=owSGVOov9pQ))*
  - *In other ways you consider pertinent*


---
## How to contribute

To contribute to [package name]:
- Install [package name] for development (see [above](#Development-installation))
- Create a branch and make your changes and/or additions. If you want to coordinate the development with the main mainteners, write xxx@yyy.com
- Commit your changes and send a pull request


---
## API documentation

You can find the API documentation of [package name] on [Read the Docs]
  - *Find the guidelines on how to create API documentation in Sphynx or Read the Docs [here](https://www.ormir.org/guidelines.html) in the section Python Documentation*


---
## Citation
- *We definitely want our code to be cited! Specify here how. Example:* 

> When using ORMIR-MIDS, please cite the following abstract:
> S. Bonaretti, M. A. Espinosa Hernandez, F. Chiumento, Y. Founas, M. Froeling, J. Hirvasniemi, G. Iori, Y. Lee, S. Matuschik, M. Monzon, F. Santini, D. Cameron. **ORMIR-MIDS:An open standard for curating and sharing musculoskeletal imaging data.** 24th International Workshop on Quantitative Musculoskeletal Imaging (QMSKI) The Barossa Valley, South Australia. November 3-8, 2024.
 
- *To know how to make your code citable by getting a Zenodo DOI, read this [blog post](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content) or watch this [video](https://www.youtube.com/watch?v=gp3D4mf6MHQ)*

---
## License
- *Although your GitHub repository contains a license, specify the license again for clarity*
- *If you are not familiar with open source licences, you can browse [choosealicense.com](https://choosealicense.com/licenses/), read the paper [A Quick Guide to Software Licensing for the Scientist-Programmer](https://doi.org/10.1371/journal.pcbi.1002598), or watch [this video (from minute 4)](https://www.youtube.com/watch?v=GlAnKGBnhFY)*

---

## Legal aspects
- *You can specify the legal aspects of your project. Here is an example:* 

> This code is freely available only for research purposes.
> The software has not been certified as a medical device and, therefore, must not be used for diagnostic purposes.
> Commercial use of the provided code and the pre-trained models is strictly prohibited, since they were developed using the medical datasets under restrictive licenses.

---
## Acknowledgments

- *Acknowledgments to collaborators and funding agencies*


---

ReadMe file created using the [template](https://github.com/ORMIRcommunity/templates/blob/main/ORMIR_readme_template.md) of the [ORMIR community](https://www.ormir.org/) (version 1.0, 2023)