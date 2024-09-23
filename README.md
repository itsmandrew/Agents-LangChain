# Agents-LangChain

Testing playground for testing Agents in LangChain

# Setting up

## 1. Create a new Conda environment

```bash
conda create --name myenv python=3.x
```

Replace `myenv` with your desired environment name and `3.x` with the Python version you want (e.g., 3.9).

## 2. Activate the environment

```bash
conda activate myenv
```

## 3. Install required packages

```bash
conda install package1 package2 package3
```

Replace `package1`, `package2`, etc. with the packages you need.

## 4. Install Jupyter in the environment

```bash
conda install jupyter
```

## 5. Install ipykernel

```bash
conda install ipykernel
```

## 6. Add the environment as a Jupyter kernel

```bash
python -m ipykernel install --user --name=myenv --display-name="Python (myenv)"
```

Replace `myenv` with your environment name. The `display-name` is what will show up in Jupyter's kernel list.

## 7. Launch Jupyter Notebook

```bash
jupyter notebook
```

## 8. Select your new kernel

When creating a new notebook, select your new kernel ("Python (myenv)") from the dropdown menu.

## Additional Commands:

- List all Conda environments:

  ```bash
  conda env list
  ```

- List all Jupyter kernels:

  ```bash
  jupyter kernelspec list
  ```

- Remove a Jupyter kernel:

  ```bash
  jupyter kernelspec uninstall myenv
  ```

- Remove a Conda environment:
  ```bash
  conda env remove --name myenv
  ```
