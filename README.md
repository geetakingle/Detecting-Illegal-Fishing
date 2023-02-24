# Detecting Illegal Fishing in Real-time

![Python version](https://img.shields.io/badge/Python%20version-3.9%2B-lightgrey)
![GitHub last commit](https://img.shields.io/github/last-commit/geetakingle/Detecting-Illegal-Fishing)
![GitHub repo size](https://img.shields.io/github/repo-size/geetakingle/Detecting-Illegal-Fishing)
![Type of ML](https://img.shields.io/badge/ML-Supervised%2FSemi--Supervised-red)
![ML Lib](https://img.shields.io/badge/ML%20Lib-scikit--learn-blueviolet)
![License](https://img.shields.io/badge/License-MIT-green)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

Badges from [here](https://shields.io/)

### Authors

- [@geetakingle](https://www.github.com/geetakingle)

I have a passion for the oceans. They play a huge role in climate and support the lives of millions of people. Illegal, unreported, and unregulated (IUU) fishing is a major concern for long term sustainability for the fishing industry and ocean health. It undermines the efforts of fishers that employ legal and ethical means of fishing, threatens vulnerable populations of sea life, and contributes to declining ocean health

By using supervised and semi-supervised learning, I decided to develop an Anomaly Detection model that detects IUU activities using loitering events on any given trip for any given vessel, using real-time data obtained from Global Fishing Watch (GFW)

## Key Findings

### There is a linear seperable boundary between loitering signatures of vessels exhibiting IUU vs. non-IUU behaviours. This linear boundary can be exploited to develop a comprehensive Anomaly Detection Model that can detect IUU signatures in real-time

## Table of Contents

  - [Problem Statement](#problem-statement)
  - [Data source](#data-source)
  - [Methods](#methods)
  - [Tech Stack](#tech-stack)
  - [Quick Peek at Results](#quick-peek-at-results)
  - [Conclusions and Lessons Learned](#conclusions-and-lessons-learned)
  - [Limitations and Further Improvements](#limitation-and-further-improvements)
  - [License](#license)


## Problem Statement

Illegal, unreported, and unregulated (IUU) fishing result in ocean exploitation and frequently use slave labour (blatant violations of human rights). Furthermore, IUU fishing is detrimental to the long-term sustainability of the fishing industry. It undermines the efforts of fishers that employ legal and ethical means of fishing, threatens vulnerable populations of sea life, and contributes to declining ocean health.

This model classifies IUU events in real-time from a loitering event (as described by [Global Fishing Watch](https://globalfishingwatch.org/faqs/what-is-loitering-event/)). Real-time data can be obtained from Global Fishing Watch's [API](https://globalfishingwatch.org/our-apis/)

## Data Source

No explicit dataset was readily available. I used secondary datasets from current research conducted by Global Fishing Watch (GFW) to create the pertinent dataset required for this analysis: 

- Illegal human trafficking on Ships: Through eyewitness accounts, prosecution data, and machine learning, GFW has classified vessel characteristics and movement data for ships suspected to be engaged in human trafficking from. This dataset, found here, contains labelled responses per ship per year (illegal trafficking yes/no) with anonymized ship IDs from 2012 to 2018. Each datapoint is one ship’s cumulative operating characteristics every year, with the dataset containing 66,369 samples.
    - Dataset [here](https://github.com/emlab-ucsb/slavery-in-fisheries.git)

- Loitering events: By analyzing GPS and AIS data, GFW has identified loitering events (under a certain set of rules) for ships from 2012 to 2019. This dataset includes characteristics of the loitering event, also called trip signature in this report, for given ship IDs. Each datapoint is one loitering event, with the dataset containing 190,344 samples.
    - Dataset [here](https://globalfishingwatch.org/data-download/datasets/public-revealing-the-supply-chain-at-sea-2021)


## Methods



## Tech Stack


## Quick Peek at Results


## Conclusions and Lessons Learned


## Limitations and Further Improvements

adf

## License

MIT License

Copyright (c) [2022] [Geetak Ingle]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

About the License here: [MIT license](https://choosealicense.com/licenses/mit/) 