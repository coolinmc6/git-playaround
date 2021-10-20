# Readme

Setup:
- new repo with two files: `index.js` which is good code and `largeFile.js` which is
like a `dist` folder with minified files that I don't need. First iteration will be
just a single file as opposed to a folder.
- This is what I think the steps are:
  - update readme and push to github
  - create a new branch `feature`
  - make a small change to index.js and change largeFile.js
  - push to `feature` branch
  - checkout main again and add largeFile.js to gitignore
  - rebase
  