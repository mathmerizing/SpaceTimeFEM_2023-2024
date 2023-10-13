1. Install Conda, c.f. [Conda Installation](https://docs.anaconda.com/free/anaconda/install/linux/).

2. Create a separate conda environment for FEniCS.
```bash
conda create -n fenics_env
```

3. Activate the conda environment.
```bash
conda activate fenics_env
```

4. Install FEniCS. 
```bash
conda install -c conda-forge fenics               
```

5. Check if installation successfully.
```bash
python3 -c "import dolfin; print(dolfin.__version__)"
```
Output like: `2019.1.0`

6. Install Matplotlib.
```bash
conda install -c conda-forge matplotlib
```

7. Install Numpy.
```bash
conda install numpy
```

8. Install Scipy. 
```bash
conda install -c anaconda scipy
```