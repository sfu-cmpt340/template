# SFU CMPT 340 Project Template -- Replace with project title
This repository is a template for your CMPT 340 course project.
Replace the title with your project title, and **add a snappy acronym that people remember (mnemonic)**.

## Timesheet
Create a timesheet (excel, google sheets, ...) where you track per student the time and tasks completed/participated for this project
<a name="intro"></a>

## Video/demo/gif
Record a short 2-5 min video or gif showcasing your work.

## 1. Introduction
A few words on the problem this project solves, a few images before/after. 

<a name="demo"></a>
### 1.1 Example demo

A minimal example to showcase your work

```python
from amazing import amazingexample
imgs = amazingexampe.demo()
for img in imgs:
    view(img)
```


## Table of contents
1. [Introduction](#intro)

    1.2 [Demo](#demo)

2. [Installation](#installation)

3. [Reproducing this project](#repro)

4. [Project report](#proj)

5. [Guidance](#guide)


## What to find where

Explain briefly what files are found where

```bash
repository
├── src                          ## source code of the package itself
├── scripts                      ## scripts, if needed
├── docs                         ## If needed, documentation   
├── README.md                    ## You are here
├── requirements.yml             ## If you use conda
```

<a name="installation"></a>

## 2. Installation

Provide sufficient instructions to reproduce and install your project. 
Provide _exact_ versions, test on CSIL or reference workstations.

```bash
git clone $THISREPO
cd $THISREPO
conda env create -f requirements.yml
conda activate amazing
```

<a name="repro"></a>
## 3. Reproduction
Demonstrate how your work can be reproduced, e.g. the results in your report.
```bash
mkdir tmp && cd tmp
wget https://yourstorageisourbusiness.com/dataset.zip
unzip dataset.zip
conda activate amazing
python evaluate.py --epochs=10 --data=/in/put/dir
```
Data can be found at ...
Output will be saved in ...

<a name="project"></a>
## 4. Project report

Link to overleaf for project report.

<a name="guide"></a>
## 5. Guidance

- Use [git](https://git-scm.com/book/en/v2)
    - Do NOT use history re-editing (rebase)
    - Commit messages should be informative:
        - No: 'this should fix it', 'bump' commit messages
        - Yes: 'Resolve invalid API call in updating X'
    - Do NOT include IDE folders (.idea), or hidden files. Update your .gitignore where needed.
    - Do NOT use the repository to upload data
- Use [VSCode](https://code.visualstudio.com/) or a similarly powerful IDE
- Use [Copilot for free](https://dev.to/twizelissa/how-to-enable-github-copilot-for-free-as-student-4kal)
- Sign up for [Github educaction](https://education.github.com/) 
