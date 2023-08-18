# FYP Project



## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.


## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/2985-st1505/fyp-project.git
git branch -M main
git push -uf origin main
```

## Development Setup 

- [ ] Make new environment and install required libraries with the following command:

for Git Bash:
```
python -m venv env
source env/Scripts/activate
pip install -r requirements.txt
```

for Windows Terminal:
```
python -m venv env
.\env\Scripts\activate
pip install -r requirements.txt
```

- [ ] Run the program with the following command:

```
python appplication/main.py
```

## Deployment: Python to EXE using Pyinstaller

- [ ] Export the project to a folder with the following command:

```
cd application
pyinstaller main.spec
```

- [ ] Test the exe with the following command:

For Git Bash:
```
cd application/dist/main
./main.exe
```

For Windows Terminal:
```
cd application/dist/main
main.exe
```
- [ ] Zip the 'main' folder under application/dist for distribution.

## Quicktest

- [ ] Go to the dist folder under application and download the zip.

## Working in teams

### Warning: Multiple people modifying the same file would most likely cause conflicts when merging; create a duplicate and mark where the changes are made before merging and combine the code afterward to avoid conflict.

- [ ] Start with 'git pull' to get the latest code on your master branch:
```
git pull
```

- [ ] To add a feature to / modify the code, make a branch and do your work on that branch:
```
git branch <feature name you are working on>
```
TBC
