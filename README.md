# How-to for Contributing to microcks.io documentation refactoring process 🙌

To contribute to microcks.io **refactor-doc-org** branch, please follow these steps:

1. **Check Latest Reporting:**
    Review the latest reporting and open issues related to your contribution. Example: [Issue #100](https://github.com/microcks/microcks.io/issues/100).

2. **Create an Issue:**
    If you would like to contribute, create an issue on the file or error you wish to address. Example: [Issue #102](https://github.com/microcks/microcks.io/issues/102).
    ![Create a documenation enhancement issue](./Create%20Docs%20Issue.png)

3. **Clone the Repository:**
    Clone the microcks.io repository to your local machine:
    ```bash
    mkdir my-contrib-to-doc
    cd my-contrib-to-doc
    git clone https://github.com/microcks/microcks.io.git
    ```
    > Cloning into 'microcks.io'...
    > 
    > remote: Enumerating objects: 4343, done.
    >
    > remote: Counting objects: 100% (364/364), done.
    >
    > remote: Compressing objects: 100% (117/117), done.
    >
    > remote: Total 4343 (delta 265), reused 282 (delta 247), pack-reused 3979
    >
    > Receiving objects: 100% (4343/4343), 161.63 MiB | 23.77 MiB/s, done.
    >
    > Resolving deltas: 100% (2345/2345), done.

4. **Switch Branch:**
    Switch to the branch where you want to make your contribution. Example: refactor-doc-org
    ```bash
    cd microcks.io
    git status
    ```
    > On branch master
    >
    > Your branch is up to date with '**origin/master**'.
    >
    > nothing to commit, working tree clean
    ```bash
    git switch refactor-doc-org
    ```
    > branch 'refactor-doc-org' set up to track '**origin/refactor-doc-org**'.
    > Switched to a new branch 'refactor-doc-org'
    ```bash
    git status
    ```
    > On branch refactor-doc-org
    >
    > Your branch is up to date with '**origin/refactor-doc-org**'.
    >
    > nothing to commit, working tree clean

5. **Create a New Branch:**
    Create a new branch for your contribution.
    ```bash
    git checkout -b my-contrib-to-doc-issue101
    ```

6. **Make Modifications:**
    Make your contributions and modifications to the files using your favorite IDE. For example:
    ```bash
    diff .lycheeignore ../../microcks.io/.lycheeignore
    ```
    > 43,44d42
    > < https://www.linkedin.com/in/madihar/
    ```bash
    git status
    ```
    > On branch my-contrib-to-doc-issue101
    >
    > Changes not staged for commit:
    >
    > (use "git add <file>..." to update what will be committed)
    > (use "git restore <file>..." to discard changes in working directory)
    >
    > modified:   .lycheeignore
    >
    > no changes added to commit (use "git add" and/or "git commit -a")

7. **Commit Changes:**
    Stage and commit your changes with a descriptive message.
    ```bash
    git add .lycheeignore
    git commit -s -m "Add https://www.linkedin.com/in/madihar/ to .lycheeignore as URL is OK, remove LinkedIn rate limit error"
    ```
    > [my-contrib-to-doc-issue101 de1a027] Add https://www.linkedin.com/in/madihar/ to .lycheeignore as url is OK, remove linkedin rate limit error
    >
    > 1 file changed, 2 insertions(+)

8. Push Changes:
    Push your commit to the remote repository.
    ```bash
    git push -u origin my-contrib-to-doc-issue101
    ```
    > Enumerating objects: 5, done.
    >
    > Counting objects: 100% (5/5), done.
    >
    > Delta compression using up to 10 threads
    >
    > Compressing objects: 100% (3/3), done.
    >
    > Writing objects: 100% (3/3), 386 bytes | 386.00 KiB/s, done.
    >
    > Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
    >
    > remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
    >
    > remote:
    >
    > remote: Create a pull request for 'my-contrib-to-doc-issue101' on GitHub by visiting:
    >
    > remote:      https://github.com/microcks/microcks.io/pull/new/my-contrib-to-doc-issue101
    >
    > remote:
    >
    > To https://github.com/microcks/microcks.io.git
    >
    >* [new branch]      my-contrib-to-doc-issue101 -> my-contrib-to-doc-issue101
    >
    > branch 'my-contrib-to-doc-issue101' set up to track 'origin/my-contrib-to-doc-issue101'.

9. Create a Pull Request:
    Create a pull request on GitHub. Visit the link provided after pushing your changes.
    ![Create a documenation PR](./Create%20Docs%20PR%20on%20branch%20refactor-doc-org.png)

10. Complete the Pull Request:
    Review and complete the pull request on GitHub. Select the correct branch and follow the instructions provided.

All steps completed. Your contribution is now under review and should be merge (if all good) shortly 🎉

