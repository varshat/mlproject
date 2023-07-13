# End to end ml project
Steps
1. create a new repo omn git
2. create a same name folder on your drive
3. open Anaconda and copy the project folder path and typr code . to open vs code
4. create a conda environment by conda create -p venv python==3.8 -y
5. activate the conda env
6. connect to git using git init
7. Add readme file from vs code, add and commit the file using git add README.md and git commit -m "first commit"
[ if it ask for identity then run following lines
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
to set your account's default identity.]
8. git branch -M main
9. git remote add origin https://github.com/varshat/mlproject.git
10. git push -u origin main
11. Note -> git remote -v is to synch with own repository