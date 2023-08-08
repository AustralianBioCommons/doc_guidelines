Bioinformatics software documentation guidelines
==============

## Description

This repository allows anyone to create simple boilerplate documentation for any bioinformatics software, using guidelines that have been co-created by the Australian BioCommons and members of the community.

- This template repository contains a set of guidelines for documenting bioinformatics software (e.g. tools and workflows).
- The initial guideline version uploaded to GitHub was informed by current documentation practices and structures used in the GitHub community.
- Subsequent versions have been modified and updated with input from Australian BioCommons engagements with infrastructure partners and the bioinformatics community.
- Typical files are included, such as a `LICENSE`, `CITATION.cff` and `change_log.md`
- These guidelines will be further developed as needed to meet the requirements of the Australian BioCommons community.

You can use this repository as:

1. A **base template** for a new GitHub repository. 
2. A **source of templates or ideas** that you can use in your existing repositories. 

> **If you use these guidelines, please cite this work :)**
> 
> Gustafsson, J., Davis, B., de la Pierre, M., Stott, A., Beecroft, S., Downton, M., Edwards, R., Chew, T., & Samaha, G. (2023). Australian BioCommons Documentation Guidelines (Version 1.5.0) [Computer software]


## Quick start guide (using repository as a template)

1. Clone repository and use it as a template for a new repository
2. Replace `README.md` with one of the files available in the `documentation_templates` directory, or create your own custom README here: https://readme.so/
3. Update the recommended files, if the required information is available (`LICENSE`, `CHANGE_LOG` and `CITATION.CFF`)
4. Update, or delete, the optional files (i.e. `codemeta.json`)
5. Delete elements you do not require (`documentation_templates` directory, original `README.md`)


## Usage guide

When your documentation is ready, this README file should be deleted and replaced with either:
- A suitable template from the `documentation_templates/` directory, or 
- A custom `README`. You can create custom content easily @ https://readme.so/.


### 1. Replace the repository `README.md`

A README.md is the explainer file for your software or project. 

If you have cloned / copied this repository, you need to replace this README with either: 

1. One of the templates from the `documentation templates` directory:
   1. Rename the template documentation file to `README.md`,
   2. Move the file into the root directory of the repository,
   3. Complete the necessary sections of the template, and 
   4. Delete the other headings

2. Create your own custom README content @ https://readme.so/

These are the current templates that are available in `documentation_templates/`:
- `tools.md`: template for documenting software tools.
- `workflows.md`: template for documenting computational workflows.
- `infrastructure_optimisation.md`: template for documenting software optimisation required for specific compute infrastructures (cloud, HPC, other).
- `benchmarking.md`: template for documenting benchmarking outcomes for software.


### 2. Update the recommended files

The files that we recommend you always include are detailed below.

| File | Purpose  | What you need to do!                                                                                                                                                                                     |
|------|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|LICENSE.md| The license that indicates how someone can reuse your software or project. | Select a license (https://choosealicense.com/) and copy the license text into this file.                                                                                                                 |
|CHANGE_LOG.md| A log of the changes made for each version / release. | Update this file when you make changes to your software or project.    |
|CITATION.cff| A standard file type that indicates how someone should cite your software or project. | Update this file with the citation metadata for your software or project. GitHub will auto-detect this file and create a citation export option for you.                                                   |


### 3. Update the optional but useful file(s)

This folder contains useful files that you can include in your repository.

`codemeta.json`: this is a standard metadata file type from the [CodeMeta Project](https://codemeta.github.io/). You can easily generate your own `codemeta.json` using this resource https://codemeta.github.io/create/
 

### 4. Delete files and directories you do not need

These are guidelines only, and that means you can modify, update or delete elements of the file and directory structure to suit your specific use case.


## Citing this repository

> If you use this template repository, or any of its documentation elements, please use the following citation:
> 
> Gustafsson, J., Davis, B., de la Pierre, M., Stott, A., Beecroft, S., Downton, M., Edwards, R., Chew, T., & Samaha, G. (2023). Australian BioCommons Documentation Guidelines (Version 1.5.0) [Computer software]


## Contributing

Anyone is welcome to contribute to these documentation guidelines in the following ways: 

1. Create an issue, or
2. Create a new branch of the repository and generate a pull request (PR)

> If you have contributed, please also add your name to the section below!


# Acknowledgements & attributions

The guideline template is supported by the Australian BioCommons via Bioplatforms Australia funding, the Australian Research Data Commons (https://doi.org/10.47486/PL105) and the Queensland Government RICF programme. Bioplatforms Australia and the Australian Research Data Commons are enabled by the National Collaborative Research Infrastructure Strategy (NCRIS).

The BioCommons would also like to acknowledge the contributions of the following individuals and institutions to these documentation guidelines:

- Johan Gustafsson (Australian BioCommons, University of Melbourne) [@supernord](https://github.com/supernord)
- Brian Davis (National Computational Infrastructure) [@Davisclan](https://github.com/Davisclan)
- Marco de la Pierre (Pawsey Supercomputing Centre) [@marcodelapierre](https://github.com/marcodelapierre)
- Audrey Stott (Pawsey Supercomputing Centre) [@audreystott](https://github.com/audreystott)
- Sarah Beecroft (Pawsey Supercomputing Centre) [@SarahBeecroft](https://github.com/SarahBeecroft)
- Matthew Downton (National Computational Infrastructure) [@mattdton](https://github.com/mattdton)
- Richard Edwards (University of New South Wales) [@cabbagesofdoom](https://github.com/cabbagesofdoom)
- Tracy Chew (University of Sydney) [@tracychew](https://github.com/tracychew)
- Georgina Samaha (University of Sydney) [@georgiesamaha](https://github.com/georgiesamaha)


# Citations

- Druskat, S., Spaaks, J. H., Chue Hong, N., Haines, R., Baker, J., Bliven, S., Willighagen, E., Pérez-Suárez, D., & Konovalov, O. (2021). Citation File Format (Version 1.2.0) [Computer software]. https://doi.org/10.5281/zenodo.5171937
- Jon Ison and others, Tools and data services registry: a community effort to document bioinformatics resources, Nucleic Acids Research, Volume 44, Issue D1, 4 January 2016, Pages D38–D47, https://doi.org/10.1093/nar/gkv1116
- Carole Goble, Stian Soiland-Reyes, Finn Bacall, Stuart Owen, Alan Williams, Ignacio Eguinoa, Bert Droesbeke, Simone Leo, Luca Pireddu, Laura Rodríguez-Navas, José Mª Fernández, Salvador Capella-Gutierrez, Hervé Ménager, Björn Grüning, Beatriz Serrano-Solano, Philip Ewels, & Frederik Coppens. (2021). Implementing FAIR Digital Objects in the EOSC-Life Workflow Collaboratory. Zenodo. https://doi.org/10.5281/zenodo.4605654
- Matthew B. Jones, Carl Boettiger, Abby Cabunoc Mayes, Arfon Smith, Peter Slaughter, Kyle Niemeyer, Yolanda Gil, Martin Fenner, Krzysztof Nowak, Mark Hahnel, Luke Coy, Alice Allen, Mercè Crosas, Ashley Sands, Neil Chue Hong, Patricia Cruse, Daniel S. Katz, Carole Goble. 2017. CodeMeta: an exchange schema for software metadata. Version 2.0. KNB Data Repository. doi:10.5063/schema/codemeta-2.0

