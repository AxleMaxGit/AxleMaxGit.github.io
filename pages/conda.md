### Conda Cheatsheet  

#### list available virtual environments   
  
conda env list

---

#### actiate a conda virtual environment to allow specific versions of python/jupyter/etc   
  
conda activate *\<my-env\>*
  
---

#### to create a new env see...  
  
[conda cheatheet](https://conda.io/docs/_downloads/conda-cheatsheet.pdf)
  
---

#### Check the current version of Python   
  
python \-\-version
  
---

#### update Python version  
  
conda update python
  
---

#### list installed packages   
  
conda list

---  

#### update all packages  
  
conda update \-\-all
  
---

#### (re)install jupyter    
  
conda install jupyter
  
---

#### (re)install ipykernel (let's you create & edit kernels) 
  
conda install ipykernel
  
---

#### to manage jupyter kernels  

#### list kernels...  
  
jupyter kernelspec list  

---
  
#### delete kernels...   
jupyter kernelspec uninstall kernel-name
  
---  
#### add new kernel...   
python -m ipykernel install --user --name kernel-name --display-name "Python (kernel-name)"  

.
