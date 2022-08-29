# ELE510
ELE510 - bildebehandling


## Working with conda env

Creating a empty env
````
    conda create -y --name <env_name> python=3.7
````

Creating a env from envirment.yml file
````
    conda env create -f environment.yml
````
---

## Saving enviroment configurations.
````
conda activate <env_name>
````

````
conda list -e > requirements.txt
````

````
conda env export > <env_name>.yml
````