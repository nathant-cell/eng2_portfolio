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

12. `uv run mkdocs gh-deploy # publish and push the site` 

## Pip