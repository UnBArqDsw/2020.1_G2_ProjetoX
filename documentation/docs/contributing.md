# Contributing

To contribute to this project follow the guide on how to contribute.

1- Create a fork or clone the repository.
````Git
git clone https://github.com/UnBArqDsw/2020.1_G2_TCLDL.git
````
2- If you want to change something, create a branch following the branch policy of this project.

3- Commit you change following the commit policy of this project

4- Create a pull request following the Pull Request policy

## Branches Policy

The <b> Branches </b> of the project must include the following specifications:

* The beginning of the branch name must be informing which group it belongs to, being:
    * feature: For adding features or changes to an existing one; 

    * bug: For bug fixes;


* The name of the branch must be related to the issue number separated by a slash('/')

* Each branch is aimed at solving a single issue, after closing the issue the branch must be deleted

````Git
Exemplo: feature/1
````
### Branch Flow

The project will adopt a git flow based on git-flow:

 * master: Is the main branch of the repository and plays the role of the production environment. It only accepts duly tested and validated code, so that all insertions made therein will be the project releases;

 * develop: is the branch that will concentrate all the new functionalities of the project, where it will perform the role of concentrating the work of the development environment, bug fixing and finalization of tests;

 * feature (feat): type of branch used for the development of a new project feature, so the name of the branch should be "feature/" and the number of the issue in github. Ex: “feature/001”;

 * Bugfix (bug): Branch to fix bugs in production;


## Commits Policy

The <b> Commits </b> of the project must include the following specifications:

* Must be written in English and use the imperative verbs

```` git
Example: update project readme
````

* For joint work, use co-authored to include as a contributor in the commit message body:
```` git
add signin feature

Co-authored-by: Fulano <funalo@outlook.com>
````

## Pull Request Policies



## Document Versioning
| Author | Date | Version | Modification |
|---|---|---|---|
| Mikhaelle Bueno| 06/09/20 | 1.1 | Document creation and edit |