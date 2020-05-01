# Women Who Code Philadelphia - Getting Started with Open Source

## 1. Setup
* [Sign up](https://github.com/join) for a GitHub account
* [Install git](https://help.github.com/articles/set-up-git/)

## 2. Find an issue to work on
* Make sure to read the Contributor Guidelines (if available) for the project you want to contribute to. For this project, comment on the issue so people know you're working on it.

## 3. Fork this repository
* Click the "Fork" button at the top right. This will create a fork of this project in your GitHub account.

## 4. Clone your fork locally
* Open your fork and click the "Clone or download" button. Copy the URL - it should be of the format: 
```
https://github.com/<your GitHub username>/wwcode-philly-open-source
```
* Open a terminal on your computer and clone your fork using the URL you just copied:
```
git clone <URL to your fork>
```

## 5. Create a branch
* Go back to the terminal on your computer and create a branch for your changes
```
cd wwcode-philly-open-source
git checkout -b <name of your branch>
```

## 6. Make your changes and commit them
* Change the file
* Commit your changes
```
git add <file>
git -m "your commit message"
```
* Push your changes to your fork on GitHub
```
git push origin <name of your branch>
```

## 7. Create a pull request
* Go back to your fork in GitHub
* Click on the "Compare & pull request" button
* Add comments - you can mention the issue by number, for example "Relevant Issue = #1".
* Click on "Create pull request" button to submit the pull request

## 8. Wait for feedback from the maintainer
* Maintainer may request changes
* If everything looks good, maintainer will accept your changes and merge them
* You'll get a notification email once the changes are merged
