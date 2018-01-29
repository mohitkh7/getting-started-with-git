# Getting started with Git

This repository is for first time contributer to get accustomed with git. There is a simple excercise which will help you understand git better.

### How to start ?

1. First, fork this repository to your account.

2. Clone this repository (this would make rebasing easier).
    ```
    git clone https://github.com/mohitkh7/getting-started-with-git.git
    ```

3. Add a remote to your forked repository. This remote will be needed to push your changes to your repo.
    ```
    git remote add myfork https://github.com/<username>/getting-started-with-git.git
    ```

4. Create a new branch and switch to it. (make sure you are on master before doing this).
    ```
    git branch mybranch
    git checkout mybranch
    ```
    'mybranch' can be replaced by your preferred name for the branch.
    The above to commands are equivalent to the following
    ```
    git checkout -b mybranch
    ```

5. Complete the exercise given below.

6. After you are done making changes, push the branch to your fork.
    ```
    git push -u myfork mybranch
    ```

7. Then create a Pull Request from that branch using GitHub.

## Exercise

### Exercise 0 - Introduce yourself
Inside the Introduction folder create a new file < your_username >.md and write your brief introduction using markdown syntax.

For any help related to markdown you can refer this [guide](https://guides.github.com/features/mastering-markdown/).