# app_template_kotlin

This is a starter project for samples w/ dependencies, copyright, and
package and project structure configured. The following is a list of
things that are setup in this project.

1. Kotlin
2. Gradle plugin version
3. Dependencies for Anko, support libraries
4. Project structure for `com.developerlife.sample`
5. `.gitignore` file
6. Needless test sources and gradle configuration removed

# Usage instructions

## 1. Example of "forking" this template repo into `my_new_sample` repo
1. Go to [github.com/new](https://github.com/new) and create a new empty repo called `my_new_sample`.
2. Clone this new repo. Use Terminal to go to your `~/github` folder and type `git clone https://github.com/nazmulidris/my_new_sample.git`
3. Add an upstream remote to this repo, by using Terminal. Go to your `~/github/my_new_sample` folder and type `git remote add upstream https://github.com/nazmulidris/app_template_kotlin.git`
4. Pull from the original repo by typing `git pull upstream master`.
5. Now you can just push this into your new repo by typing `git push origin master`.

```
# After creating your new and empty my_new_sample repo on github.com
cd ~/github/
git clone https://github.com/nazmulidris/my_new_sample.git
cd my_new_sample
git remote add upstream https://github.com/nazmulidris/app_template_kotlin.git
git pull upstream master
```

Notes 
- When this template is updated, you can go to you new repo (eg: `my_new_sample`) in Terminal and type `git pull upstream master` and handle the merge conflicts, to update your project to latest gradle configuration and dependencies.
- More info on forking your own repo [here](https://www.tilcode.com/fork-your-own-repo-on-github/).

## 2. Refactor the template project to match `my_new_sample`
- In Android Studio, just rename the `sample` folder to whatever your project is (eg: `my_new_sample`) which will update `AndroidManifest.xml`
- Go into the `build.gradle` for the `app` module, and update the 
`applicationId` w/ the new name, eg `com.developerlife.my_new_sample`.

## 3. Start coding! 
