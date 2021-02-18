# postpro_genericVAlidationTool
This repo is aimed to holed different **monitoring**, **analysing**, and 
**validation** scripts for simulaitons based on [TSMP](https://www.terrsysmp.org/).


## Getting Started

As this repository contains submodules (git-repos inside git-repos) a little 
special treatment is needed to clone this repo. Basically there are two options:

**Option 1**
Clone the repository as usual 
``` bash
git clone https://icg4geo.icg.kfa-juelich.de/SoftwareTools/postpro_genericVAlidationTool.git
```
and initialize and update the submodules afterwards
``` bash
cd postpro_genericVAlidationTool
git submodule init 
git submodule update
```
>**Note:** you have to type the GitLab password for each submodule!

**Option 2**
Combine individual steps of Option 1:
``` bash
git clone --recurse-submodules https://icg4geo.icg.kfa-juelich.de/SoftwareTools/postpro_genericVAlidationTool.git
```
> **Note:** you have to type the GitLab password for each submodule!