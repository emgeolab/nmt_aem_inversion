# AEM inversion for data acquired at New Mexico
Processing and inversion of airborne electromagnetic data acquired at New Mexico


## Setup

### Anaconda

If you do not already have Anaconda you can download it [here](https://www.anaconda.com/download/success). 

*Be sure to download the correct package for your operating system.*
 

### Step 1: Download the AEM processing and inversion notebooks

To clone this repository, open up an Anaconda terminal and navigate to where you want this repository stored on your computer.

Then run
```
git clone 
```
to clone the repository, and `cd` into the `earthscope-mt-course-2024` directory
```
cd nmt_aem_inversion
```

### Step 2: Create `em` conda environment

#### Create environment


From inside of the `nmt_aem_inversion` repository, create the `em` conda environment
```
conda env create -f environment.yml
```

and activate the environment

```
conda activate em
```

### Step 3: Launching the notebooks

Once you have activated the conda environment, you can launch the notebooks

```
jupyter lab
```

Jupyter will then launch in your web-browser.

