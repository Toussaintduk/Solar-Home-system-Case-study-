# Solar Home System (SHS) Energy Consumption Analysis

## Overview

This repository analyzes **hourly electricity consumption data from 1,000 Solar Home Systems (SHS)** as part of an **Energy Data Analytics** study. The analysis focuses on understanding household energy-use patterns and supporting data-driven SHS sizing.

## Dataset

- **Systems:** 1,000
- **Resolution:** Hourly
- **Analysis period:** First 365 days
- **Consumption unit:** Wh
- **Time representation:** Elapsed hourly observations

Zero values represent no recorded consumption, while missing values (`NaN`) are retained as missing observations.

## Analysis

The analysis includes:

- Hourly and daily energy consumption
- Representative 24-hour load profiles
- Daytime and nighttime consumption
- Peak consumption and peak hours
- Daily consumption statistics
- Autocorrelation of daily demand
- Load-profile clustering
- Battery capacity requirements

## Tools

```text
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook

##Data source
Data repository for 'Understanding long-term energy use in off-grid solar
home systems in sub-Saharan Africa'
A pre-print of the publication that refers to this dataset is available at
https://arxiv.org/abs/2502.14630. This repository contains the household
load demand data for 1,000 solar home systems used in the research.
The file included in this repository is:
final_anon_hourly.csv
Each column in this CSV file represents the hourly electricity demand (in
watt-hours, Wh) for a single household with a solar home system in sub-
Saharan Africa. Each row corresponds to an hourly time step, all starting
at midnight. The dataset includes between 391 - 1232 days of data for each
household and is intended to support research into household energy use,
demand modelling, and energy access system design.
Please note:
- Timestamps are not included in the file. The data assumes a regular,
continuous hourly sampling interval, each starting at midnight.
- All demand values are energy consumption values recorded by the solar
home systems, interpolated to hourly values.
Please see the included license file, also repeated below.
LICENSE
These data are copyright (c) 2025, BBOXX Ltd., The Chancellor, Masters and
Scholars of the University of Oxford, and the 'Understanding long-term
energy use in off-grid solar home systems in sub-Saharan Africa'
researchers. All rights reserved.
This 'Understanding long-term energy use in off-grid solar home systems in
sub-Saharan Africa' dataset is made available under the Creative Commons
Attribution-NonCommercial 4.0
International License (https://creativecommons.org/licenses/by-nc/4.0/).
THIS DATA IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE
USE
OF THIS DATA, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE
