
[![Python application test with Github Actions](https://github.com/Deepika-TestRepo/azurehello/actions/workflows/main.yml/badge.svg)](https://github.com/Deepika-TestRepo/azurehello/actions/workflows/main.yml)
# azure hello
you can create the same by following the steps:

first open CLI in azure portal
connect with BASH

then generate keys by ssh-keygen -t rsa 
and paste these key to GITHUB settings in SSH keys
then go to current directory of folder
e.g cd azurehello

then start scaffolding by creating makefile, requirements.txt, python files
by using command touch Makefile (for creation of files)
then use command vim Makefile for opening file in vim editor)
to bring the cursor to command line press **esc**
to save and exit the file use :wq
for pasting the file use command i and ctrl+shift+v
once all files are completed with coding and all

Then
Create a python virtual environment and source it if not created
python3 -m venv ~/.myrepo
source ~/.myrepo/bin/activate
Then run command "make all"
then check test is passed if yes, then run the below commands
then check git status
then git commit -m "message"
git push

