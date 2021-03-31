1. Create environment with python and jupyter
> conda create -n faiss python=3.7 jupyter
2. Add dependencies
> pip install -r requirements.txt

or 

> pip install -r requirements-all.txt

3. Add kernel to jupyter
> python -m ipykernel install --user --name faiss --display "faiss"