# flutter_demo

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

Project Sub module

- git submodule add github_url

Take pull from library
- cd libraryName
- git status
- git pull origin main

For existing current code revert
- git submodule update
- git status

Remove Sub module
- git submodule deinit -f libraryName
- rm -rf .git/modules/libraryName/
- rm -rf .gitmodules
- git rm -f libraryName/

/////
- git status
- git add .
- git commit -m “remove submodule”
- git push origin master


Checkout branch
-  git submodule update --init --recursive --remote
- git checkout origin/base_components


For committing

git commit -am “comment”


//add all projects

- Git submodule update —init


