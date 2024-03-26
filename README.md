# AT4BR_homework_4
This is repository for 4th exercises session 

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
To do that, you need to clone desired repoitory.

```
> git clone <repository_url>

```
This command will let you download the code to your computer.

**Congratulaions, you created your first repository!**

### Working on your project
- branch

Branch is a new version of the main repository - it means you can change it in the way you want without demaging your main repository. 

There are few commands connected with branches
    - First things first - you need to create a new branch
    ```
    > git branch <branch_name>

    ```
    - Now when we have our branch we can move to it. To do so you need to use this command:

    ```
    > git checkout <branch_name>

    ```
    - another useful feature can be merging the branches

    ```
    > git merge <branch_name>

    ```
    
    - if you want to delete branch you can do it by adding a simple flag `-d`

    ```
    > git branch -d <branch_name>

    ```
    - If you want to see the list of your branches you just need to do this:

    ```
    > git branch

    ```

- 