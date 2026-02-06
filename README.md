# Hydroframe Demo

This demo showcases the ParFlow CLM model

NOTE: To run this demo, you’ll need to [sign up and generate a PIN](https://hydrogen.princeton.edu/pin). PINs are valid for 48 hours; after they expire, you must request a new PIN to regain access to the dataset.

### Instructions

**1 - Go to NSF National Research Platform JupyterHub.** If the option is not visible for you, please contact ndp@sdsc.edu to request access to the server.
**2 - Reserve resources.** In the JupyterHub spawner page, set these parameters:
  - Region: Any
  - Zone: Any
  - GPUs: 0
  - Cores: 1
  - RAM: 16 GB
  - GPU Type: Any
    
**3 - Start the server.** Click on Start Server and wait for your server to initialize.
**4 - Set your storage (optional).** Once in JupyterLab, use the File Browser to navigate to a storage folder for your work.
**5 - Select workspace.** In the Widget, select this workspace from the list of workspaces.
**6 - Clone repository.** Use the Clone into Current Folder button in the Widget to clone the workspace's repository.
**7 - Install requirements.** Using the File Browser, navigate to the hydroframe directory within the cloned repository. Return to the Widget and confirm that you are inside the hydroframe directory using the Current Folder window. Once you confirm that you're in the right folder, install the dependencies by clicking the Install requirements.txt button. Upon successful installation, you will see a confirmation pop-up and a log file with the installed libraries will be generated automatically. In the case that your .log file is not automatically generated, click the Install requirements.txt button one more time. Sometimes, libraries are installed, but the file is not generated at first.
**8 - Run the Jupyter notebook.** Open and run the hydroframe_demo.ipynb notebook in JupyterLab.
**9 - Stop Your JupyterHub Server.** To stop the server, navigate to File → Hub Control Panel → Stop Server.
