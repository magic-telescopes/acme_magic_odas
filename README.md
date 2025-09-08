# ACME-sponsored 1st MAGIC Open Data-Analysis School

This repository contains the material for the [1st open MAGIC data-analysis school](https://acme-magic-odas.sciencesconf.org/).
The corresponding data will soon be provided as well. 

## Context
Gamma-ray astronomy at the highest energy has been traditionally conducted with proprietary data and software.
Before the advent of the next-generation open gamma-ray Observatories like the Cherenkov Telescope Array (CTAO),
the MAGIC Collaboration - among others - has devoted significant effort into standardising its own archival observations
in order to share them with the Astronomical Community at large.
This data-analysis school represents a milestone in this process.
Scientists with interests in the analysis of VHE (E > 100 GeV) gamma-ray data are invited to join this two-day remote workshop
to learn how to analyse the MAGIC telescopes data.
A data set of MAGIC archival observations will be publicly released for the school.
The analysis will be conducted with [Gammapy](https://gammapy.org/), an open-source software for gamma-ray astronomy.
Given the endeavours of the VHE community into standardising data format and analysis tools,
the experience acquired in the school will be directly transferable to the analysis of other current or future VHE instruments.
All the material (lessons and hands-on recording, data, and software) will remain openly available in this repository after the school.

## Introductory material
If you are not familiar with Gamma-ray astronomy, you can find an [introductory lecture](https://youtu.be/xvbSOgyHxrQ) on this field and another on the [analysis of its data](https://youtu.be/HqxcLnD2uMs) in the [MAGIC Collaboration's YouTube Channel](https://www.youtube.com/@magictelescopes8632/).

## Software Requirements
The only software required to successfully participate in the school is [Gammapy](https://gammapy.org/).   
Check the installation instructions [here](https://docs.gammapy.org/2.0/getting-started/index.html#installation) and follow through this whole [section](https://docs.gammapy.org/2.0/getting-started/index.html#recommended-setup) to download the tutorial datasets and set some variables. 
These are needed by some notebooks in the school to work properly.   

## Material for the school

### Analysis notebooks
Clone this git repository to your own machine, e.g.:
```bash
git clone https://github.com/magic-telescopes/acme_magic_odas.git
```
To run the notebooks, remember to select a kernel with the `gammapy-2.0` environment.

### Gammapy-data
You'll need `gammapy-datas` to run the notebooks. You can also download them via git:
```bash
git clone https://github.com/gammapy/gammapy-data
```
Then you should set environment variable `$GAMMAPY_DATA` to the local folder where you have saved gammapy-data.
```bash
export GAMMAPY_DATA=/path/to/gammapy-data
```

### Data set for the school
The data set for the school are available in [zenodo](https://zenodo.org/records/17064461).
