# mitre att&ck  
Project with python scripts for querying MITRE ATT&CK.  

## Installation  
Go to directory where you want your files and clone the repository from Github
```
git clone https://<username>:<token>@github.com/jdalexan32/mitre.git
```

## Prepare Jupyter Notebook environment    
1. Create venv
   ```
   python -m venv venv
   ```   
2. Activate venv (powershell)
   ```
   venv\Scripts\Activate.ps1
   ```
3. Install Jupyter inside venv
   ```
   pip install jupyter
   ```
4. Install Kernel  
   ```
   ipython kernel install --user --name=mitre-attack
   ```  
   ```
   python -m ipykernel install --user --name=mitre-attack
   ```  

   Replace mitre-attack with the name you want for your Jupyter kernel.
       
6. Install the Bash Kernel  
   ```
   pip install bash_kernel
   ```
   ```
   python -m bash_kernel.install
   ```
  
## Install requirements   
```
pip install -r .\requirements.txt
```

## Start Jupyter Notebook 
   Browser -   
   ```
   Jupyter notebook
   ```
   Or
   
   Open Visual Studio Cose and select the Virtual Environment Kernel in Jupyter  
   In the Jupyter interface click on the “Kernel” menu, choose “Change Kernel” and select the virtual environment kernel you created 
