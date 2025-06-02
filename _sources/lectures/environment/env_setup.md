# Environment Setup

Follow these steps to download the lesson files, install dependencies, and launch JupyterLab so you can browse the lessons.

---
1. **Open a new terminal**  
   - In JupyterLab, click the **+** (Launcher) button in the left sidebar.  
   - Under **Other**, click **Terminal** to open a shell.
![OOD Interactive Apps](./img/b1.png)
![OOD Interactive Apps](./img/b2.png)
   - **Note:** The terminal often starts at the server’s root (`/`). You need to move into your working folder and tell JupyterLab where to look, in the new terminal window paste the following:
     ```bash
     cd   # change into your main working directory
     pwd  # print the full path, e.g. /global/home/users/hgamarro
     ```
   - In JupyterLab’s top menu, go to **File → Open From Path**, then paste the output of `pwd`. This will point your File Browser at the correct directory.
![OOD Interactive Apps](./img/b3.png)

2. **Download the lessons repository**
- In the new terminal window paste the following 
```bash
cd
git clone https://github.com/hgamarro/wrf-docs.git
mv wrf-docs/src/ lessons
rm -rf wrf-docs
rm lessons/LICENSE.md lessons/eeds-logo.png
```

3. **Install the JupyterLab notebook-viewer extension**  

- This extension adds a **Table of Contents** panel for any folder of notebooks.
- Click extension tab on the left toolbar of Jupyter lab (looks like a puzzle peice)
- search for "jupyterlab-jupyterbook-navigation" and install 
- Once it’s installed:

1. In the **File Browser**, navigate into the `lessons/` folder.  
2. Open the **Table of Contents** side-panel (click the “JB” icon in the left sidebar).  
3. Click any lesson title in the **Table of Contents** to jump to that notebook.
![OOD Interactive Apps](./img/b4.png)
![OOD Interactive Apps](./img/b5.png)
![OOD Interactive Apps](./img/b6.png)

> **Note:**  
> - If the lesson you open is a **Markdown file** (`.md`), you’ll probably need to use the **Terminal** for the lesson 
> - If the lesson is a **Notebook** (`.ipynb`), you can open and interact with it directly in JupyterLab.  

![OOD Interactive Apps](./img/b7.png)
![OOD Interactive Apps](./img/b8.png)



4. **Install required Python packages**
- Create new Conda env based on savio instuctions
- https://docs-research-it.berkeley.edu/services/high-performance-computing/user-guide/ood/jupyter/#using-a-conda-environment

```bash
module load anaconda3/2024.02-1-11.4
conda create --name=learning ipykernel
source activate learning
python -m ipykernel install --user --name learning
```
- Once new conda env is installed, we can add new python packages that will be useful for the lessons

```bash
conda install -c conda-forge pooch netcdf4 h5py curl libcurl openssl numpy matplotlib pandas xarray scipy cartopy -y
```

<!-- 3. **Install required Python packages**  
```bash
conda install -c conda-forge \
  numpy \
  pandas \
  matplotlib \
  xarray \
  netcdf4 \
  -y
``` -->





