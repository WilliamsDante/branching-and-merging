# Branching and Merging
This is a project describing how the changes made, through the branches created by Tom and Jerry are been reviewed and merged back into the main branch of the repository.

## Creating a pull request

### 1. Tom's Branch
Switch to the branch where tom's changes where made, by clicking on the branch dropdown menu and selection the branch, the **update navigation**.

![update navigation](./img/01.%20update%20navigation.png)

* Create a new pull request, click on the **contribute** button, then the **open pull request** button

![Toms pull request](./img/02.%20pull%20request%20-%20tom.png)

Open a pull request
* Add a title and a description

![creating pull request](./img/03.%20create%20pull%20request%20.png)

* Merge the pull request to the main branch

![merge request](./img/04.%20merge%20request%20.png)

![merged](./img/05.%20branch%20merged%20.png)

### 2. Jerry's Branch
Switch to jerry's branch in the terminal `git checkout add-contact-info`

Push jerry's changes to the main branch `git push origin add-contact-info`

![git push](./img/06.%20Jerry's%20push.png)

* Create a pull request for Jerry's branch just as you did for Tom's branch

![Jerrys pull request](./img/07.%20jerrys%20pull%20request%20.png)

![creating pull request](./img/08.%20creating%20pull%20request.png)

* Merge Jerry's pull request to the main branch

![jerrys merge](./img/09.%20pull%20merged%20.png)

Changes made by both branches have now been successfully merged to the main.
