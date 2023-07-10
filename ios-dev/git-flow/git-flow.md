---
marp: true
theme: uncover
class: invert
---

# Git Flow

---

## Definition

Gitflow is a Git Workflow that defines a strict model of branches, mainly oriented to releases, usually for large projects. Gitflow creates two branches:

- master
- develop

---

Develop is basically the full history of our project. The master branch would only be our production branch, this means that all the code in the master branch is functional, documented, and bug-free.

---

## Feature/Bugfix Branches
Does your project need a new improvement? The feature branch is the one indicated. This branch is based in the develop branch, here we can do the commits of our new functionality.

---

## Release Branch
The release branch, basically allows us to create a "release" of the project, that's mean will be sending our project to a production environment. Unlike other branches, the release branch will be unified with both develop and master. And they will be tagged.

---

## Hotfix
The hotfix branch helps us to correct errors in production. This is the only branch that derives from the master. Once the error is corrected, we must end the branch, it will be merged with master and develop. The master branch will be labeled with the version number.

---

Branch diagram 

![image height:6in](https://leonardo-casamayor.github.io/gist-resourses/ios-dev/GitFlow.png)

---

## Resourses

- [Gitflow - Introduction](https://dev.to/angelmtztrc/gitflow-introduction-l8i)
- [Aprende Git de manera sencilla](https://desarrollowp.com/blog/tutoriales/aprende-git-de-manera-sencilla-git-flow/)

---

## Further Reading

- [State of CI/CD and the omnipresent git flow](https://medium.com/burdaforward/state-of-ci-cd-and-the-dreaded-git-flow-fce92d04fb07)