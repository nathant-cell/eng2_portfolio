# UV and Pip

## UV 
I created this using UV because I was still learning and using UV makes it a lot easier. 

`mkdir eng2_portfolio # make the folder`

`cd eng2_portfolio # navigate into the folder`

`uv pip install mkdocs mkdocs-material # install mkdocs and material into uv's environment` 

`uv run mkdocs new . # initialize an mkdocs site` 

`uv run mkdocs serve # run a local dev server` 

`git init`

`git add .` 

`git commit -m "Initial MkDocs portfolio"` 

`git branch -M main` 

`git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/eng2_portfolio.git` 

`git push -u origin main` 

Then you use this after you commit and sync your changes:

`uv run mkdocs gh-deploy`

## Pip
With Pip it runs slower and you have to make different commands. The only reason you would really use Pip is because not everything supports UV. 

`mkdir project # creates a folder`

`cd project # navigates into that folder`

`python -m venv .venv # creates a virtual environment`

`source .venv/bin/activate # activates and enters the vitrtual environement on a mac`

`pip install (your choice of library) # installs your choice of python libraries`

`python main.py # run virtual environment`

`git clone (link of the repo) # reate the folder with the repo`

`cd (repo name) #navigate into repo`

`uv sync`

`pip install -r requirements.txt`