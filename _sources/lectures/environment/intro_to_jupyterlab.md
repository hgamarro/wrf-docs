# Intro to JupyterLab

[JupyterLab](https://jupyterlab.readthedocs.io) will be our primary method for
interacting with the computer. JupyterLab contains a complete environment for
interactive scientific computing which runs in your web browser. Jupyter is an
open source python project that was started by scientists like yourselves who
wanted a more effective way to interact with their computers.

## Using Jupyter notebooks via the interactive Open OnDemand service

### Running a notebook via Open OnDemand

1. Connect to https://ood.brc.berkeley.edu
2. Just after logging in with your BRC username and one-time password (OTP), the initial OnDemand screen presents a welcome screen. Click the "Interactive Apps" pulldown.
![OOD Interactive Apps](./img/a1.png)
3. **Which Jupyter server should I pick?**  
   - **Heavy or long-running jobs:**  
     Choose **“Jupyter Server – compute via Slurm using Savio partitions”**. This reserves a dedicated compute node for resource-intensive analyses.  
   - **Quick tests or light work:**  
     Choose **“Jupyter Server – exploration, debugging on (free) shared nodes”**. This runs on a shared server (up to 8 GB RAM and a few CPU cores) and doesn’t count against your allocation.  
![OOD Interactive Apps](./img/a2.png)
4. **Start your Jupyter session**  
   1. Keep default job name: `OOD_Jupyter`  
   2. Leave **Software modules** blank (Anaconda is loaded automatically)  
   3. Select **SLURM Partition**: `savio3`  
   4. Select **SLURM Account/Project Name**: `co_aiolos`  
   5. Select **SLURM QoS Name**: `aiolos_savio3_normal`  
   6. Set **Number of Compute Nodes** to `1`  
   7. Set **Wall Clock Time (hours)** to `3`  
   8. Click **Launch**  
   9. When your server is ready, click **Launch**  
![OOD Interactive Apps](./img/a3.png)
5. **Connect to your notebook**  
   Once your session status turns **Running**, click the **Connect to Jupyter** button. This will open your Jupyter environment in a new browser tab.  
![OOD Interactive Apps](./img/ood_jupyter_submit.png)
![OOD Interactive Apps](./img/ood_jupyter_connect.png)


JupyterLab has excellent documentation. Rather than repeat that documentation
here, we point you to their docs. The following pages are particularly relevant:

- [The JupyterLab Interface](https://jupyterlab.readthedocs.io/en/stable/user/interface.html)
- [Working with Files](https://jupyterlab.readthedocs.io/en/stable/user/files.html)
- [The Text Editor](https://jupyterlab.readthedocs.io/en/stable/user/file_editor.html)
- [Notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)
- [Terminals](https://jupyterlab.readthedocs.io/en/stable/user/terminal.html)
- [Managing Kernels and Terminals](https://jupyterlab.readthedocs.io/en/stable/user/running.html)

You will gain experience and familiarity with JupyterLab over the course of the
summer.

## Markdown

Throughout the course, we will write rich text documents using Markdown.
Here are some useful references on Markdown syntax.

- [Official Markdown Documentation](https://daringfireball.net/projects/markdown/)
- [Markdown Guide / Basic Syntax](https://www.markdownguide.org/basic-syntax) -
  A more user-friendly syntax guide.

  
<!-- - change figs to current version of OOD since these are old.
- Use the free for the to start
- then add a point about compute 
- easy way to screenshot 
- add instuction to get to scratch 
- install custom env 
- show pic of actual env 
- install the notebooks 
- install the opackjage to let them view the lessons 
- go over lesson 
- add WRF stuff 
-->


<!-- ## Our Course JupyterHub

[JupyterHub](https://jupyter.org/hub) is multi-user Jupyter environment designed for companies, classrooms and research labs.
The Columbia version of this course uses a cloud-based JupyterHub environment
managed by [2i2c](https://2i2c.org/infrastructure/):

[![Launch JupyterHub](https://img.shields.io/badge/jupyterhub-us--central1--b.gcp.pangeo.io-orange?style=for-the-badge&logo=jupyter)]([https://pangeo.2i2c.cloud/](https://us-central1-b.gcp.pangeo.io/))
 -->