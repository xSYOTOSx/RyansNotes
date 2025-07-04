# Edits and Pushg the site 

### Setting up the virtual enviroment 

After opening Visual Studeo, in the termininal input the collowing codes.

```py title="Virtual Enviroment" linenums="1"
python -m venv venv
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\venv\Scripts\activate
mkdocs serve
```

to close the virtual enviroment just press Ctrl+C in the terminal. 

### Pushing the changes to GitHub 
```py title="Commit and Push" linenums="1"
git add .
git commit -m "Add Comment here"
git push origin main
```
 
Checkout your site at [https://xsyotosx.github.io/RyansNotes/](https://xsyotosx.github.io/RyansNotes/)

Do i have to use mkdocs gh-deploy??