  # backend-development-workspace

Created by Donte Samuels
This repository documents my journey in learning backend development, Git, and version control." > README.md

git add README.md
git commit -m "Initial commit: added basic README with name and purpose"

mkdir -p unit-02-version-control unit-03-backend-scripting unit-04-advanced-scripting unit-05-restful-apis

echo "# Unit 2: Version Control" > unit-02-version-control/README.md
echo "# Unit 3: Backend Scripting" > unit-03-backend-scripting/README.md
echo "# Unit 4: Advanced Scripting" > unit-04-advanced-scripting/README.md
echo "# Unit 5: RESTful APIs" > unit-05-restful-apis/README.md

git add .
git commit -m "Added initial project folders for upcoming units with README files"

echo "# Learning Log

My Backend Development Goals:
- Learn Git and GitHub version control
- Build backend apps using Node.js and Express
- Understand REST API design and structure
- Strengthen my problem-solving and debugging skills
" > learning-log.md

git add learning-log.md
git commit -m "Created learning-log.md to document backend development goals"




echo "# Git Command Reference

Common Git Commands:
- git status → check repo status
- git add . → stage all changes
- git commit -m 'message' → save changes locally
- git push → upload changes to GitHub
- git pull → sync updates from GitHub
- git log --oneline → view commit history
- git checkout -b branch-name → create and switch branches
" > git-reference.md

git add git-reference.md
git commit -m "Created git-reference.md as my personal Git cheat sheet"



