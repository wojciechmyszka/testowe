# Adding locally hosted code to GitHub

## [In this article](https://docs.github.com/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#in-this-article)

- [About adding existing source code to GitHub](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#about-adding-existing-source-code-to-github)

- [Adding a local repository to GitHub with GitHub CLI](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#adding-a-local-repository-to-github-with-github-cli)

- [Adding a local repository to GitHub using Git](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#adding-a-local-repository-to-github-using-git)

- [Further reading](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#further-reading)

Learn how to add existing source code or repositories to GitHub from the command line using GitHub CLI or Git Commands. Then, share your code and invite others to work with you.

## About adding existing source code to GitHub

If you have existing source code or repositories stored locally on your computer or private network you can add them to GitHub by typing commands in a terminal. You can do this by typing Git commands directly, or by using GitHub CLI.

GitHub CLI is an open source tool for using GitHub from your computer's command line. GitHub CLI can simplify the process of adding an existing project to GitHub using the command line. To learn more about GitHub CLI, see "[About GitHub CLI](https://docs.github.com/en/github-cli/github-cli/about-github-cli)."

**Tip:** If you're most comfortable with a point-and-click user interface, try adding your project with GitHub Desktop. For more information, see "[Adding a repository from your local computer to GitHub Desktop](https://docs.github.com/en/desktop/guides/contributing-to-projects/adding-a-repository-from-your-local-computer-to-github-desktop)" in the *GitHub Desktop Help*.

**Warning:** Never `git add`, `commit`, or `push` sensitive information to a remote repository. Sensitive information can include, but is not limited to:

- Passwords
- SSH keys
- [AWS access keys](http://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSGettingStartedGuide/AWSCredentials.html)
- API keys
- Credit card numbers
- PIN numbers

For more information, see "[Removing sensitive data from a repository](https://docs.github.com/en/articles/removing-sensitive-data-from-a-repository)."

## Adding a local repository to GitHub with GitHub CLI

1. In the command line, navigate to the root directory of your project.

2. Initialize the local directory as a Git repository.

    ```shell
    git init -b main
    ```

3. Stage and commit all the files in your project

    ```shell
    git add . && git commit -m "initial commit"
    ```

4. To create a repository for your project on GitHub, use the `gh repo create` subcommand. When prompted, select **Push an existing local repository to GitHub** and enter the desired name for your repository. If you want your project to belong to an organization instead of your user account, specify the organization name and project name with `organization-name/project-name`.

5. Follow the interactive prompts. To add the remote and push the repository, confirm yes when asked to add the remote and push the commits to the current branch.

6. Alternatively, to skip all the prompts, supply the path to the repository with the `--source` flag and pass a visibility flag (`--public`, `--private`, or `--internal`). For example, `gh repo create --source=. --public`. Specify a remote with the `--remote` flag. To push your commits, pass the `--push` flag. For more information about possible arguments, see the [GitHub CLI manual](https://cli.github.com/manual/gh_repo_create).

## Adding a local repository to GitHub using Git

1. [Create a new repository](https://docs.github.com/en/articles/creating-a-new-repository) on GitHub.com. To avoid errors, do not initialize the new repository with *README*, license, or `gitignore` files. You can add these files after your project has been pushed to GitHub.![Create New Repository drop-down](https://docs.github.com/assets/cb-11427/images/help/repository/repo-create.png)

2. Open Terminal.

3. Change the current working directory to your local project.

4. Initialize the local directory as a Git repository.

    ```shell
    $ git init -b main
    ```

5. Add the files in your new local repository. This stages them for the first commit.

    ```shell
    $ git add .
    # Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
    ```

6. Commit the files that you've staged in your local repository.

    ```shell
    $ git commit -m "First commit"
    # Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
    ```

7. At the top of your repository on GitHub.com's Quick Setup page, click to copy the remote repository URL.![Copy remote repository URL field](https://docs.github.com/assets/cb-25662/images/help/repository/copy-remote-repository-url-quick-setup.png)

8. In Terminal,

     

    add the URL for the remote repository

     

    where your local repository will be pushed.

    ```shell
    $ git remote add origin  <REMOTE_URL> 
    # Sets the new remote
    $ git remote -v
    # Verifies the new remote URL
    ```

9. Push the changes

     

    in your local repository to GitHub.com.

    ```shell
    $ git push origin main
    # Pushes the changes in your local repository up to the remote repository you specified as the origin
    ```

## Further reading

- "[Adding a file to a repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository#adding-a-file-to-a-repository-using-the-command-line)"