While the Jupyter notebook allows to read the code and interpret the fixed outputs directly, the interactive interpretations such as those requiring selections from dropdowns will need the code to be executed. To run the code, please follow the following steps:
1. Ensure correct working directory in CLI, and setup a virtual environment with `virtualenv venv`. 
2. Once created, activate it with `source venv/bin/activate`.
3. Install the dependencies with `pip install -r requirements.txt`
4. Additionally, `graphviz` is required which can be installed via brew by running `brew install graphviz`.
5. Run `jupyter lab` in CLI to launch the jupyter lab server on localhost and execute each of the cells in `main.ipynb`.