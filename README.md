### Install Repo:

```bash
git clone https://github.com/IbrahimAlobid2/ML.git
```

### Creating a Conda Environment 

```bash
    conda create -n ml-env
```

### Activating a Conda Environment 

```bash
    conda activate ml-env
```


###  Install Dependencies  
Run the following command to install the required packages:  
```bash
    pip install numpy pandas scikit-learn seaborn jupyter
```



##  Using a Conda Environment in Jupyter Notebook

Once you've created and activated your Conda environment, follow these steps to use it within Jupyter Notebook.

### 1. Install `ipykernel` in the Conda Environment

This package allows you to register your environment as a Jupyter kernel.

```bash
conda install ipykernel
````

### 2. Create a Kernel for the Conda Environment

Replace `myenv` with your environment's name.

```bash
python -m ipykernel install --user --name=myenv
```

This will create a new kernel associated with the `myenv` environment, making it available inside Jupyter Notebook.

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```


