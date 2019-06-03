# mkdocs-sample

This is a small proof of concept on how to use mkdocs for creating documentation.

mkdocs installation is easy following the instructions on [mkdocs homepage](https://www.mkdocs.org/)

clone this repo.
cd into root 
"mkdocs serve" starts a local server on localhost:8000 which allows you to see the documentation as you edit it

edit the doc
push to master branch

mkdocs build build the documentation under the site directory
mkdocs gh-deploy deploys the branch to corresponding [github page)[https://alaincaron.github.io/mkdocs-sample/]

mkdocs also support deploying to S3 or any other hosting site


