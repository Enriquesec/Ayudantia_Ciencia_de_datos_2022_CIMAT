# Ayudantia_Ciencia_de_datos_2022_CIMAT
Aquí se recopilaran todos los codigos necesarios en las ayudantías, como las soluciones de las tareas.


Para la seción del 24 de enero del 2022. Installar Anaconda. 

Para Windows: 
 - Anaconda (o miniconda): https://www.anaconda.com/download/#windows
 - Abrir Anaconda e instalar Jupyter Notebook
 - Correr Jupyter Notebook


Para Linux/Mac:
- Miniconda (https://varhowto.com/install-miniconda-ubuntu-20-04/): 
	1. wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
	2. chmod +x Miniconda3-latest-Linux-x86_64.sh
	3. ./Miniconda3-latest-Linux-x86_64.sh
- Después:
	```
	conda create -n ciencia_de_datos
	conda activate ciencia_de_datos
	conda install ipykernel         
	ipython kernel install --user --name=ciencia_de_datos-kernel
	```
- Por último:
	```
	conda deactivate
	conda install jupyter
	jupyter notebook
	```






