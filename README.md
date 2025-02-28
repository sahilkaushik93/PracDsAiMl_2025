# Create Virtual Env
1. python -m venv venv 
2. venv\Scripts\activate
3. to deactivate venv: deactivate
# Create requirements.txt
1. write all package names required
2. pip install -r requirements.txt
# Attaching with GitHub
#### Creating a new repository via command line
* echo "# PracDsAiMl_2025" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/sahilkaushik93/PracDsAiMl_2025.git
* git push -u origin main
#### Push an existing repository via command line
* git remote add origin https://github.com/sahilkaushik93/PracDsAiMl_2025.git
* git branch -M main
* git push -u origin main
# API Keys
#### This is method 1
1. create a file .env
2. install python-dotenv
3. use load_env() to load all apis in app script
#### This is method 2
1. create a .streamlit folder
2. create a secrets.toml file
3. save api secrets e.g. key = value
4. use it in app script by "st.secrets(key)"