# Kedro starter for DAI (Data Analytics & Insight ) 


## Overview

Personally I use Cookiecutter to initiate data analytics project

Simply run : 

```bash
cookiecutter https://github.com/Dennis055/dai-analytics.git
```



```bash
pip install kedro==0.16.5
kedro new --starter git+https://github.com/Dennis055/dai-analytics.git
cd <my-project-name>  # change directory into newly created project directory
```

Install the required dependencies:

```bash
kedro install
```

## How to install dependencies

Declare any dependencies in `src/requirements.txt` for `pip` installation and `src/environment.yml` for `conda` installation.

To install them, run:

```
pip install -r src/requirements.txt
```

Now you can run the project:

```bash
kedro run
```

To visualise the default pipeline, run:
```bash
kedro viz
```

This will open the default browser and display the following pipeline visualisation:

![](./images/pipeline_visualisation_with_layers.png)
