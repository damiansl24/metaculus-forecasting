## Outline/guide of this folder

All directories within this folder contain one question
from metaculus. The format of all folders will be:

## README.md
-> this document will contain the question, any sources that 
   I consulted while answering the question, and my thought
   process behind solving the problem

## python files/jupyter notebooks
-> These will be the actual code I use to analyze the data I
   find or pull.

And any datasets I can upload I will. 

## SETUP
When setting up the repository: I made to make a kernel (pointing to the venv)
python -m ipykernel install --user \
  --name metaculus-venv \
  --display-name "Metaculus (venv)"

  Copied that into the terminal, and then in the jupyter notebook I set it to that kernel.