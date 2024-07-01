# mitre att&ck #

## Clone repo ##
```git clone <repo url```  

## Create venv (ps) ##
1. Active venv  
   ```venv\Scripts\Activate.ps1```

2. Install Jupyter inside venv  
   ```pip install jupyter```

3. Install Kernel  
   ```pip install ipython```  
   ```pip install ipkernel```  

   ```ipython kernel install --user --name=mitre-attack```  
   ```python -m ipykernel install --user --name=mitre-attack```  
 
     Replace mitre-attack with the name you want for your Jupyter kernel.  

4.	Install the Bash Kernel  
  ```pip install bash_kernel```  
  ```python -m bash_kernel.install```  
 
5.	Start Jupyter Notebook  
  ```Jupyter notebook```
 
6.	Select the Virtual Environment Kernel in Jupyter  
  In the Jupyter interface click on the “Kernel” menu, choose “Change Kernel” and select the virtual environment kernel you created  
 
## Install requirements ##
  ```pip install -r requirements.txt```
