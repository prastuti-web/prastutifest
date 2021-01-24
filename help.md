# Note: Please make sure when you push the code on github add virtual enviornment folders in .gitignore

###### for writing in help.md you can follow this link: https://medium.com/@saumya.ranjan/how-to-write-a-readme-md-file-markdown-file-20cb7cbcd6f

1. Creating virtual enviornment:   ```python -m venv <folder name>```
2. Initializing git in project:    ```git init```
3. Creating requirement.txt and freeze:   ```pip freeze --local > requirement.txt```
   * It stores all the installed packages.
   * Just run ```pip install -r requirement.txt``` for install all the packages required in the project
      that are already installed.
4. If you want to create django project ```django-admin startproject <project name>``` 
5. If you want to create django app ```python manage.py startapp <app name>```
