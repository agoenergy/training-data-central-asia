<!--
-*- coding: utf-8 -*-
SPDX-FileCopyrightText: 2026 PyPSA-SPICE-Central-Asia-Training Developers
SPDX-License-Identifier: MIT
-->

# Modelling Data for PyPSA-SPICE Central Asia Training

🎯 Weclome to the data repository to manage input and output data from PyPSA-SPICE Central Asia model for the training workshop (Kazakhstan (KZ), Kyrgyzstan (KG), and Uzbekistan (UZ)).

## 🏗️ Installation

### Step 1: Clone the PyPSA-SPICE repository

First, ensure that you clone the [PyPSA-SPICE repository](https://github.com/agoenergy/pypsa-spice) using the **Git** version control system. If you already clones the PyPSA-SPICE repository, then you can skip this step.

**Important:** the path to the directory where the repository is cloned **must not contain any spaces**.

If Git is not installed on your system, please follow the [Git installation instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

```shell title="Cloning the repository"
git clone https://github.com/agoenergy/pypsa-spice.git
cd pypsa-spice
```

### Step 2: Clone this data repository

To clone this data repository into the correct location, you will have to go into `data` folder and use the same git clone command to clone this repo inside the `data` folder.

```shell title="Cloning the training-data-central-asia repository inside data folder"
cd data
git clone https://github.com/agoenergy/training-data-central-asia.git
cd ..
```

You shall be able to see this repository clones inside the folder with a separate git version control from PyPSA-SPICE. The ensures that any changes inside the data repository will be committed to PyPSA-SPICE modelling repository.

### Step 3: Copy the base_config.yaml

Copy the `base_config.yaml` file and replace the one in the root path of PyPSA-SPICE.

