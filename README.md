# Instructions to run

Note that the dependencies require running the code in an anaconda environment.

Steps:

1. create conda env: conda create --name myenv python=3.10
2. activate anaconda env: conda activate myenv
3. pip install -r requirements.txt
4. run command: python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
5. In your editor, you must select the anaconda environment myenv