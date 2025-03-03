# HC-RecSys25

<p align="center">
<img width="1100"  src="imgs/header.png"/> 
</p>



## Setting Up Your Environment

 Create a virtual environment (optional, but recommended). This step helps isolate the dependencies of your notebooks from the system-level Python environment.

* You will find a guide 👉 [here](https://docs.conda.io/en/latest/miniconda.html) and [here](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) on how to install Conda, as well as alternative methods for creating virtual environments on macOS, Windows and Linux:

### Creating a Conda Environment:
1. To create a new Conda environment, open a new command prompt or terminal and use the following command:
    ```sh
    conda create --name hc-recsys25 python=3.9
    ```
    (Optional) Replace "hc-recsys25" with your desired environment name, 

2. Activate the new environment:
    * On macOS/Linux:
    ```sh
    conda activate hc-recsys25
    ```

    * On Windows:
    ```sh
    activate hc-recsys25
    ```
3. Install Requirements:

    First you need to install pipreqs library by running the following command:
    ```sh
    pip install pipreqs
    ```
    Now you can run the following command to install the required packages:

    ```sh
    pip install -r requirements.txt
    ```
    Once the installation is complete, all the packages specified in the requirements.txt file should be installed in your environment.


## Download resources for the hc-recsys25
 *  Run the following command to download resources:

     ```sh
    pip install gdown
    ```
     ```sh
    gdown "https://drive.google.com/uc?export=download&id=1reyiD5YEmz6Z42J03GQG6-FDRUcrlF0W"

    ```
     Unzip resourses 

     ```sh
    unzip -q resources.zip
    ```

