# AT4BR_homework_4
This is a repository for the 4th exercises session. 

Maria Koziarz, 20.03.2024

## How to use GitHub?
### Beginnings
First, you need to get a repository to work on. You can do it in two ways:

- creating new repository

you can do it using `git init`

```
> git init <repository_name>

```
- using already existing repository

To do that, you need to clone the desired repository.

```
> git clone <repository_url>

```
This command will let you download the code to your computer.

**Congratulaions, you have created your first repository!**:partying_face:

### Working on your project :woman_technologist:
- branch

    A branch is a new version of the main repository - it means you can change it in the way you want without demaging your main repository. 

    There are a few commands connected with branches:

    * First things first - you need to create a new branch 
        
        ```
        > git branch <branch_name>     
        
        ```
    
    * Now when we have our branch we can move to it. To do so you need to use this command:

        ```
        > git checkout <branch_name>

        ```
    * Another useful feature can be merging the branches:

        ```
        > git merge <branch_name>

        ```

    * If you want to delete branch you can do it by adding a simple flag `-d`

        ```
        > git branch -d <branch_name>

        ```
    * If you want to see the list of your branches you just need to do this:

        ```
        > git branch

        ```
- Add

The `add` command adds files in your working area to to the Git staging area. You can use it to add new files or changed files.

```
> git add <whatever_you_want_to_add>

```
The `add` command is important because it allows you to do succesful commit.

- commit 

The `commit` command allows you to commit changes to the repository.

```
> git commit 

```
Usually, we add `-m` flag which stands for message. This allows you to include a commit message. 

```
> git commit -m "You're doing great!"

```

- fetch 

`fetch` command let us get all the change history of a branch or repository.

```
> git fetch <name>

```
- pull

The `pull` command is a combination of `fetch` and `merge`. It is used to pull all changes from a remote repository into the branch you are working on. 

- status

The `status` command shows the current state of your Git working directory and staging area.

```
> git status

```
- diff

The `diff` commandlists out the changes between your current working directory and your staging area

```
> git diff

```
### Last but not least (actually most important) :loudspeaker:

The `push` command pushes the committed file changes from the local repository to the remote repository so others can use them.

```
> git push 

```
If you want to specify, you can add name of remote repository and branch name.

```
> git push <remote_repo> <branch_name>

```

And now you can peacfully close all windows on your computer, log out and go to rest. :smiley:

