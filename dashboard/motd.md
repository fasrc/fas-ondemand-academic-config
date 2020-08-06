  Welcome to FAS OnDemand
  ============

  With FAS OnDemand, you can:
  
    * Run Jupyter Notebooks
    * Run Rstudio
    * Open an interactive remote desktop session to a compute node
    * Browse and edit your files
    * Open a terminal connection to a login node
  
  Click `Interactive Apps` in the menu bar above and select your application of choice (Jupyter Notebook, Rstudio, Comsol Multiphysics, Remote Desktop, etc) to get going.
  
  For reference, find more information below regarding:
  
        * Jupyter Notebooks
          * Get started with Jupyter Notebooks on FAS OnDemand
          * How to install python packages in your Jupyter Notebook server
        * Rstudio
          * Get started with Rstudio on FAS OnDemand
          * How to install R packages in your Rstudio server
        * Documentation on other services and applications, such as Remote Desktop
        * Getting help
        * System status and planned downtime
  
  
  ## Jupyter Notebooks
  
  #### Get started with Jupyter Notebooks on FAS OnDemand
  
  1. On the menu bar, click `Interactive Apps` and select the Jupyter app for your class. For example, if your class is CS109a, select `Jupyter Notebook - CS109a`.
  
  ![Select-jupyter-app screenshot](./screenshots/select-jupyter-app.png?raw=true)
  
  2. On the following page, in `Allocated Time`, enter the approximate number of hours for which you would like to run your server. For example, for a 4 hour session, enter `04:00:00`. Afterwards, click `Launch`.
  
  ![Launch-jupyter-server screenshot](./screenshots/launch-jupyter-server.png?raw=true)
  
  3. On the page that follows, click `Connect to Jupyter`. A new browser tab containing the Jupyter notebooks interface will open.
  
  ![Connect-to-jupyter screenshot](./screenshots/connect-to-jupyter.png?raw=true)
  
  4. Select the jupyter kernel you want. For example, to start a notebook with the Python 3 jupyter kernel, click `New` then `Python 3`.
  
  ![Select-python-3-kernel screenshot](./screenshots/select-python-3-kernel.png?raw=true)
  
  #### How to install python packages in your Jupyter Notebook server
  
  It is probable that the package you need is already pre-installed and that you can import it in your notebooks with `import packagename`. If that is not the case, below are the steps to install a python package.
  
  1. From the jupyter notebooks interface, click `New` then `Terminal`. A terminal will open in a new browser tab.
  
  ![Open-a-terminal screenshot](./screenshots/open-a-terminal.png?raw=true)
  
  2. In the Terminal, run `pip install --user packagename`, replacing `packagename` with the python package you intend to install. E.g:
  
  ![Install-python-package screenshot](./screenshots/install-python-package.png?raw=true)
  
  
  ## Rstudio
  
  #### Get started with Rstudio on FAS OnDemand
  
  1. On the menu bar, click `Interactive Apps` and select `Rstudio Server`.
  
  ![Select-rstudio-App screenshot](./screenshots/select-rstudio-app.png?raw=true)
  
  2. On the following page, enter the `Memory Allocation in GB` and `Number of cores` depending on your compute requirements. 4GB of memory and 1 CPU core should be sufficient in most cases. Under `Allocated Time`, enter the approximate number of hours for which you'll be running your server. E.g., for 4 hours, enter `04:00:00`. Finally, under `rstudio version`, select the version of R you intend to use.
  
  ![Rstudio-server-setup screenshot](./screenshots/rstudio-server-setup.png?raw=true)
  
  3. Click `Launch`.
  
  ![Launch-rstudio-server screenshot](./screenshots/launch-rstudio-server.png?raw=true)
  
  4. On the page that follows, click `Connect to Rstudio Server`.
  
  ![Connect-to-rstudio-server screenshot](./screenshots/connect-to-rstudio-server.png?raw=true)
  
  A new browser tab containing the Rstudio interface will open.
  
  ![Rstudio-interface screenshot](./screenshots/rstudio-interface.png?raw=true)
  
  #### How to install R packages in your Rstudio server
  
  It is probable that the package you need is already pre-installed. At any rate, to install additional R packages, from the Rstudio console, run `install.packages('packagename')`. E.g, to install the package 'shiny', run `install.packages('shiny')`:
  
  ![Install-r-packages.png screenshot](.screenshots//install-r-packages.png?raw=true)
  

  ## Documentation on Other Services and Applications
  
  Refer to our [main documentation](https://docs.rc.fas.harvard.edu) to learn more on
  
    * [Virtual Desktop (VDI) through Open OnDemand](https://docs.rc.fas.harvard.edu/kb/virtual-desktop/)
    * [running jobs on the cluster and request resources](https://docs.rc.fas.harvard.edu/kb/running-jobs/)
    * [how to check your running](https://docs.rc.fas.harvard.edu/kb/convenient-slurm-commands/#Controlling_jobs) and [fairshare](https://docs.rc.fas.harvard.edu/kb/fairshare/)
    * [access scientific software in your jobs](https://docs.rc.fas.harvard.edu/kb/software/)
  
  ## Getting Help
  
  If you need help, please contact us following [these instructions](https://docs.rc.fas.harvard.edu/kb/support/), or come at visit us at our [office hours sessions](https://www.rc.fas.harvard.edu/training/office-hours/).

  ## System Status and Planned Downtime
  -------------------
  Please refer to [https://status.rc.fas.harvard.edu/](https://status.rc.fas.harvard.edu/) to get the latest information on the status of the system.

  You can find inormation on our [monthly planned maintenance window at this page](https://www.rc.fas.harvard.edu/maintenance).

