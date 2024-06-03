<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="demon_logos/Original-on-Transparent.png" alt="Logo" width="300" height="180">
  </a>

<h3 align="center">Reproducible Reporting using Markdown</h3>

  <p align="center">
    This workshop was a collaboration between the DEMON Network and the UK Reproducibility Network (UKRN), held virtually via zoom on 27/07/21.
    <br />
    Contributers: DEMON Network, UKRN
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Workshop</a>
      <ul>
        <li><a href="#quick-description">Quick Description</a></li>
        <li><a href="#background/motivation">Background/motivation</a></li>
        <li><a href="#workflow-summary">Workflow Summary</a></li>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Workshop

### Quick Description

The goal for this workshop was to teach researchers how to report their research reproducicbly using Markdown.

### Background/motivation

When performing research, it is important to guarantee that all results can be independently recreated and verified to build upon in future work. There are many tools that can be used to aid in the production of reproducible research, such as Markdown. Markdown is a useful tool for documenting and sharing your work. You can use a Markdown file to reproduce your work and export the results as a finished report.   

### Workflow Summary

1. R workshop snd excercises
2. Python workshop and excercises

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Rstudio or Python/Google Colab

### Installation

Clone the repo to download all materials
   ```sh
   git clone https://github.com/ipdgc/GP2-pathway-enrichment-pipeline.git
   ```
or browse the materials via [Github Pages](https://demon-network.github.io/markdown-workshop/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

These notebooks can be directly uploaded to your workspace on Terra. They are designed to be used on Terra with AMP-PD data, but by changing the file paths you can use these notebooks anywhere other than Terra and for any data.


### 1. First import PD GWAS summary statistics into Terra workspace

Using import_GWAS_sumstats_Manuela.ipynb. Summary statistics (excluding 23andMe data) were downloaded from https://pdgenetics.org/resources and are publicly available.


### 2. Format for FUMA 

Using format_for_FUMA_Manuela.ipynb. This saves the GWAS summary statistics in FUMA format, then you can just upload this straight to FUMA. So far we can't find a way to link/embed FUMA within Terra.

### 3. Run WebGestaltR in Terra

Using run_WebGestaltR_Manuela.ipynb. For this we used the PD GWAS significant loci (p < 5 x 10<sup>-8</sup>) annotated with the nearest genes, available from https://www.nature.com/articles/ng.3043 (Supplementary Table 2).

_For more examples, please refer to FUMA [documentation](https://fuma.ctglab.nl/tutorial) and WebGestaltR [documentation](https://cran.r-project.org/web/packages/WebGestaltR/index.html)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Event organization
* Professor David Llewellyn
* Dr. Janice Ranson
* Dr. Charlotte James
* Ms. Janice Alcott

Resource development
*

Speakers
*

Facilitators
R
*

Python
*

<p align="right">(<a href="#readme-top">back to top</a>)</p>


