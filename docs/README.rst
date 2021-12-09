# Fulbright Cátedra (August 2021)

### This repository contains jupyter notbooks for fulbright Cátedra (symposium).

## Requirements

+ The requirements for these notebooks can be installed either directly using our specification file or by manually getting the required tools.

    + Our spec file is located in the github repository: (requiredPackages.txt). You can set up your environment using `conda create -n fulbright --file requiredPackages.txt` 
    
    + Alternatively, you can also manually install the following packages to set up your environment. Most of the required packages can be obtained using `conda` as following
    
        + Let's get the jupyterlab using: `conda install -c conda-forge jupyterlab`
        
        + Plink: `conda install -c bioconda plink`
        
        + R on jupyterlba using: `conda install -c r r-essentials r-irkernel`
        
        + Don't forget to enable R in jupyter notebooks using `IRkernel::installspec()` in your R server.

        + You will also need the R packages: `install.packages("tidyverse")`, `install.packages(dplyr)`, `install.packages(plyr)`, `install.packages(reshape2)`, & `install.packages("vcfR")`
        
        + VEP tool: `conda install -c bioconda ensembl-vep`
        
        + ADMIXTURE: `conda install -c bioconda admixture`
        
        
## About the notebooks

These notebooks were created for **Fulbright Cátedra (August 2021)** and were meant to be used parallel to our presentation slides. These notebooks will guide your though most of the functionalities that are discussed during our presentations.
        
        
## About the data

The raw data required for running the notebooks is present in the `data/` folder. However, keeping the space constrains in mind, only the raw VCF files are shared. You will have to create the associated PED/BED files for processing manually. However, if you need any specific files, please reach out to us on email.


## Live broadcasting video

[Watch the YouTube video recorded live during the event here](https://www.youtube.com/watch?v=kEtmaDICvpA&t=9952s)


## Contact

Please contact king.jordan {-AT-} biology.gatech.edu for any queries/suggestions.


## Acknowledgements

+ Fulbright Colombia
+ Augusto Valderrama-Aguirre, Universidad de Los Andes
+ Leonardo Mariño-Ramírez, National Institute on Minority Health and Health Disparities, NIH 
+ Shivam Sharma, National Institute on Minority Health and Health Disparities, NIH
+ King Jordan, Georgia Institute of Technology
+ Shashwat Deepali Nagar, Georgia Institute of Technology
