# mitre att&ck  
Project with python scripts for querying MITRE ATT&CK.  

## Installation  
Clone the repository  
```
git clone https://github.com/jdalexan32/mitre.git   
```
```
cd mitre-on-jupyter   
```

## Create venv   
1. Install virtualenv (if not already installed)   
   ```
   pip install virtualenv
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
   pip install ipython
   ```
   ```
   pip install ipkernel
   ```  
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
   
7. Start Jupyter Notebook  
   ```
   Jupyter notebook
   ```
   
8. Select the Virtual Environment Kernel in Jupyter  
   In the Jupyter interface click on the “Kernel” menu, choose “Change Kernel” and select the virtual environment kernel you created 
  
## Install requirements   
```
pip install -r requirements.txt
```
