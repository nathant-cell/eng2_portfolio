# UV and Pip

## UV 
I created this using UV because I was still learning and using UV makes it a lot easier. 

1. `mkdir eng2_portfolio # make the folder`

2. `cd eng2_portfolio # navigate into the folder`

3. `uv pip install mkdocs mkdocs-material # install mkdocs and material into uv's environment` 

4. `uv run mkdocs new . # initialize an mkdocs site` 

5. `uv run mkdocs serve # run a local dev server` 

6. `git init`

7. `git add .` 

8. `git commit -m "Initial MkDocs portfolio"` 

9. `git branch -M main` 

10. `git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/eng2_portfolio.git` 

11. `git push -u origin main` 

Then you use this after you commit and sync your changes:
`uv run mkdocs gh-deploy`

## Pip
With Pip it runs slower and you have to make different commands. The only reason you would really use Pip is because not everything supports UV. 

1. `mkdir project # creates a folder`

2. `cd project # navigates into that folder`

3. `python -m venv .venv # creates a virtual environment`

4. `source .venv/bin/activate # activates and enters the vitrtual environement on a mac`

5. `pip install (your choice of library) # installs your choice of python libraries`

6. `python main.py # run virtual environment`

7. `git clone (link of the repo) # reate the folder with the repo`

8. `cd (repo name) #navigate into repo`

9. `uv sync`

10. `pip install -r requirements.txt`