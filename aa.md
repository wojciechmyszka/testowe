::: {#main-content role="main" style="scroll-margin-top:5rem"}
::: {.container-xl .px-3 .px-md-6 .my-4}
::: {.Box-sc-1gh2r6s-0 .sc-bdvvtL .cDEAYg}
::: {.Box-sc-1gh2r6s-0 .fKomXO}
::: {.d-flex .flex-items-baseline .flex-justify-between}
# Adding locally hosted code to GitHub {#adding-locally-hosted-code-to-github .border-bottom-0}
:::
:::

::: {.Box-sc-1gh2r6s-0 .sc-gsDKAQ .ehctan .iGLrqc .border-bottom .border-xl-0 .pb-4 .mb-5 .pb-xl-0 .mb-xl-0}
## [In this article](/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#in-this-article) {#in-this-article .Heading-sc-1irtotl-0 .cTXFFN .mb-1}

::: {.List__StyledList-sc-1x7olzq-0 .hSakvk}
::: {.Group__StyledGroup-sc-cnw2p9-0 .jHjLnh}
-   ::: {.Item__DividedContent-sc-yeql7o-0 .jUHGRC}
    ::: {.Item__MainContent-sc-yeql7o-1 .hxusas style="--main-content-flex-direction:row"}
    ::: {.lh-condensed .d-block .width-full}
    <div>

    [About adding existing source code to
    GitHub](#about-adding-existing-source-code-to-github){.d-block
    .width-auto}

    </div>
    :::
    :::
    :::

```{=html}
<!-- -->
```
-   ::: {.Item__DividedContent-sc-yeql7o-0 .jUHGRC}
    ::: {.Item__MainContent-sc-yeql7o-1 .hxusas style="--main-content-flex-direction:row"}
    ::: {.lh-condensed .d-block .width-full}
    <div>

    [Adding a local repository to GitHub with GitHub
    CLI](#adding-a-local-repository-to-github-with-github-cli){.d-block
    .width-auto}

    </div>
    :::
    :::
    :::

```{=html}
<!-- -->
```
-   ::: {.Item__DividedContent-sc-yeql7o-0 .jUHGRC}
    ::: {.Item__MainContent-sc-yeql7o-1 .hxusas style="--main-content-flex-direction:row"}
    ::: {.lh-condensed .d-block .width-full}
    <div>

    [Adding a local repository to GitHub using
    Git](#adding-a-local-repository-to-github-using-git){.d-block
    .width-auto}

    </div>
    :::
    :::
    :::

```{=html}
<!-- -->
```
-   ::: {.Item__DividedContent-sc-yeql7o-0 .jUHGRC}
    ::: {.Item__MainContent-sc-yeql7o-1 .hxusas style="--main-content-flex-direction:row"}
    ::: {.lh-condensed .d-block .width-full}
    <div>

    [Further reading](#further-reading){.d-block .width-auto}

    </div>
    :::
    :::
    :::
:::
:::
:::

::: {.Box-sc-1gh2r6s-0 .hFwelc}
::: {.f2 .color-fg-muted .mb-3 .Lead_container__7YW6Y testid="lead" search="lead"}
Learn how to add existing source code or repositories to GitHub from the
command line using GitHub CLI or Git Commands. Then, share your code and
invite others to work with you.
:::

::: UnderlineNav-body
Mac

Windows

Linux
:::
:::

::: {.Box-sc-1gh2r6s-0 .rgaUH search="article-body"}
::: {#article-contents}
::: {.MarkdownContent_markdownBody__2Fa4B .markdown-body}
## [![](data:image/svg+xml;base64,PHN2ZyBhcmlhLWhpZGRlbiByb2xlPSJpbWciIGNsYXNzPSJvY3RpY29uLWxpbmsiIHZpZXdib3g9IjAgMCAxNiAxNiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2IiBmaWxsPSJjdXJyZW50Q29sb3IiIHN0eWxlPSJkaXNwbGF5OmlubGluZS1ibG9jazt1c2VyLXNlbGVjdDpub25lO3ZlcnRpY2FsLWFsaWduOm1pZGRsZSI+CiAgICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTcuNzc1IDMuMjc1YS43NS43NSAwIDAwMS4wNiAxLjA2bDEuMjUtMS4yNWEyIDIgMCAxMTIuODMgMi44M2wtMi41IDIuNWEyIDIgMCAwMS0yLjgzIDAgLjc1Ljc1IDAgMDAtMS4wNiAxLjA2IDMuNSAzLjUgMCAwMDQuOTUgMGwyLjUtMi41YTMuNSAzLjUgMCAwMC00Ljk1LTQuOTVsLTEuMjUgMS4yNXptLTQuNjkgOS42NGEyIDIgMCAwMTAtMi44M2wyLjUtMi41YTIgMiAwIDAxMi44MyAwIC43NS43NSAwIDAwMS4wNi0xLjA2IDMuNSAzLjUgMCAwMC00Ljk1IDBsLTIuNSAyLjVhMy41IDMuNSAwIDAwNC45NSA0Ljk1bDEuMjUtMS4yNWEuNzUuNzUgMCAwMC0xLjA2LTEuMDZsLTEuMjUgMS4yNWEyIDIgMCAwMS0yLjgzIDB6Ij4KICAgICAgICAgPC9wYXRoPgogICAgICAgIDwvc3ZnPg==){.octicon-link}](#about-adding-existing-source-code-to-github){.doctocat-link} About adding existing source code to GitHub

If you have existing source code or repositories stored locally on your
computer or private network you can add them to GitHub by typing
commands in a terminal. You can do this by typing Git commands directly,
or by using GitHub CLI.

GitHub CLI is an open source tool for using GitHub from your computer\'s
command line. GitHub CLI can simplify the process of adding an existing
project to GitHub using the command line. To learn more about GitHub
CLI, see \" [About GitHub
CLI](/en/github-cli/github-cli/about-github-cli) .\"

::: {.extended-markdown .tip .border .rounded-1 .mb-4 .p-3 .color-border-accent-emphasis .color-bg-accent .f5}
**Tip:** If you\'re most comfortable with a point-and-click user
interface, try adding your project with GitHub Desktop. For more
information, see \" [Adding a repository from your local computer to
GitHub
Desktop](/en/desktop/guides/contributing-to-projects/adding-a-repository-from-your-local-computer-to-github-desktop)
\" in the *GitHub Desktop Help* .
:::

::: {.extended-markdown .warning .border .rounded-1 .mb-4 .p-3 .color-border-danger .color-bg-danger .f5}
**Warning:** Never `          git add         ` ,
`          commit         ` , or `          push         ` sensitive
information to a remote repository. Sensitive information can include,
but is not limited to:

-   Passwords
-   SSH keys
-   [AWS access
    keys](http://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSGettingStartedGuide/AWSCredentials.html)
-   API keys
-   Credit card numbers
-   PIN numbers

For more information, see \" [Removing sensitive data from a
repository](/en/articles/removing-sensitive-data-from-a-repository) .\"
:::

## [![](data:image/svg+xml;base64,PHN2ZyBhcmlhLWhpZGRlbiByb2xlPSJpbWciIGNsYXNzPSJvY3RpY29uLWxpbmsiIHZpZXdib3g9IjAgMCAxNiAxNiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2IiBmaWxsPSJjdXJyZW50Q29sb3IiIHN0eWxlPSJkaXNwbGF5OmlubGluZS1ibG9jazt1c2VyLXNlbGVjdDpub25lO3ZlcnRpY2FsLWFsaWduOm1pZGRsZSI+CiAgICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTcuNzc1IDMuMjc1YS43NS43NSAwIDAwMS4wNiAxLjA2bDEuMjUtMS4yNWEyIDIgMCAxMTIuODMgMi44M2wtMi41IDIuNWEyIDIgMCAwMS0yLjgzIDAgLjc1Ljc1IDAgMDAtMS4wNiAxLjA2IDMuNSAzLjUgMCAwMDQuOTUgMGwyLjUtMi41YTMuNSAzLjUgMCAwMC00Ljk1LTQuOTVsLTEuMjUgMS4yNXptLTQuNjkgOS42NGEyIDIgMCAwMTAtMi44M2wyLjUtMi41YTIgMiAwIDAxMi44MyAwIC43NS43NSAwIDAwMS4wNi0xLjA2IDMuNSAzLjUgMCAwMC00Ljk1IDBsLTIuNSAyLjVhMy41IDMuNSAwIDAwNC45NSA0Ljk1bDEuMjUtMS4yNWEuNzUuNzUgMCAwMC0xLjA2LTEuMDZsLTEuMjUgMS4yNWEyIDIgMCAwMS0yLjgzIDB6Ij4KICAgICAgICAgPC9wYXRoPgogICAgICAgIDwvc3ZnPg==){.octicon-link}](#adding-a-local-repository-to-github-with-github-cli){.doctocat-link} Adding a local repository to GitHub with GitHub CLI

1.  In the command line, navigate to the root directory of your project.

2.  Initialize the local directory as a Git repository.

                 
                  git init -b main
                 
                

3.  Stage and commit all the files in your project

                 
                  git add . && git commit -m "initial commit"
                 
                

4.  To create a repository for your project on GitHub, use the
    `           gh repo create          ` subcommand. When prompted,
    select **Push an existing local repository to GitHub** and enter the
    desired name for your repository. If you want your project to belong
    to an organization instead of your user account, specify the
    organization name and project name with
    `           organization-name/project-name          ` .

5.  Follow the interactive prompts. To add the remote and push the
    repository, confirm yes when asked to add the remote and push the
    commits to the current branch.

6.  Alternatively, to skip all the prompts, supply the path to the
    repository with the `           --source          ` flag and pass a
    visibility flag ( `           --public          ` ,
    `           --private          ` , or
    `           --internal          ` ). For example,
    `           gh repo create --source=. --public          ` . Specify
    a remote with the `           --remote          ` flag. To push your
    commits, pass the `           --push          ` flag. For more
    information about possible arguments, see the [GitHub CLI
    manual](https://cli.github.com/manual/gh_repo_create) .

## [![](data:image/svg+xml;base64,PHN2ZyBhcmlhLWhpZGRlbiByb2xlPSJpbWciIGNsYXNzPSJvY3RpY29uLWxpbmsiIHZpZXdib3g9IjAgMCAxNiAxNiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2IiBmaWxsPSJjdXJyZW50Q29sb3IiIHN0eWxlPSJkaXNwbGF5OmlubGluZS1ibG9jazt1c2VyLXNlbGVjdDpub25lO3ZlcnRpY2FsLWFsaWduOm1pZGRsZSI+CiAgICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTcuNzc1IDMuMjc1YS43NS43NSAwIDAwMS4wNiAxLjA2bDEuMjUtMS4yNWEyIDIgMCAxMTIuODMgMi44M2wtMi41IDIuNWEyIDIgMCAwMS0yLjgzIDAgLjc1Ljc1IDAgMDAtMS4wNiAxLjA2IDMuNSAzLjUgMCAwMDQuOTUgMGwyLjUtMi41YTMuNSAzLjUgMCAwMC00Ljk1LTQuOTVsLTEuMjUgMS4yNXptLTQuNjkgOS42NGEyIDIgMCAwMTAtMi44M2wyLjUtMi41YTIgMiAwIDAxMi44MyAwIC43NS43NSAwIDAwMS4wNi0xLjA2IDMuNSAzLjUgMCAwMC00Ljk1IDBsLTIuNSAyLjVhMy41IDMuNSAwIDAwNC45NSA0Ljk1bDEuMjUtMS4yNWEuNzUuNzUgMCAwMC0xLjA2LTEuMDZsLTEuMjUgMS4yNWEyIDIgMCAwMS0yLjgzIDB6Ij4KICAgICAgICAgPC9wYXRoPgogICAgICAgIDwvc3ZnPg==){.octicon-link}](#adding-a-local-repository-to-github-using-git){.doctocat-link} Adding a local repository to GitHub using Git

::: {.extended-markdown .mac}
1.  [Create a new
    repository](/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
    on GitHub.com. To avoid errors, do not initialize the new repository
    with *README* , license, or `           gitignore          ` files.
    You can add these files after your project has been pushed to
    GitHub. [ ![Create New Repository
    drop-down](/assets/cb-11427/images/help/repository/repo-create.png)
    ]{.procedural-image-wrapper}

2.  Open [ Terminal ]{.platform-mac} [ Terminal ]{.platform-linux} [ Git
    Bash ]{.platform-windows} .

3.  Change the current working directory to your local project.

4.  Initialize the local directory as a Git repository.

                  
                   $ git init -b main
                  
                 

5.  Add the files in your new local repository. This stages them for the
    first commit.

                  
                   $ git add .
        # Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD
                   
                    YOUR-FILE
                   
                   '.
                  
                 

6.  Commit the files that you\'ve staged in your local repository.

                  
                   $ git commit -m "First commit"
        # Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
                  
                 

7.  At the top of your repository on GitHub.com\'s Quick Setup page,
    click
    ![](data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld2JveD0iMCAwIDE2IDE2IiBjbGFzcz0ib2N0aWNvbiBvY3RpY29uLXBhc3RlIiBhcmlhLWxhYmVsPSJUaGUgY29weSB0byBjbGlwYm9hcmQgaWNvbiIgcm9sZT0iaW1nIj4KICAgICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTUuNzUgMWEuNzUuNzUgMCAwMC0uNzUuNzV2M2MwIC40MTQuMzM2Ljc1Ljc1Ljc1aDQuNWEuNzUuNzUgMCAwMC43NS0uNzV2LTNhLjc1Ljc1IDAgMDAtLjc1LS43NWgtNC41em0uNzUgM1YyLjVoM1Y0aC0zem0tMi44NzQtLjQ2N2EuNzUuNzUgMCAwMC0uNzUyLTEuMjk4QTEuNzUgMS43NSAwIDAwMiAzLjc1djkuNWMwIC45NjYuNzg0IDEuNzUgMS43NSAxLjc1aDguNUExLjc1IDEuNzUgMCAwMDE0IDEzLjI1di05LjVhMS43NSAxLjc1IDAgMDAtLjg3NC0xLjUxNS43NS43NSAwIDEwLS43NTIgMS4yOTguMjUuMjUgMCAwMS4xMjYuMjE3djkuNWEuMjUuMjUgMCAwMS0uMjUuMjVoLTguNWEuMjUuMjUgMCAwMS0uMjUtLjI1di05LjVhLjI1LjI1IDAgMDEuMTI2LS4yMTd6Ij4KICAgICAgICAgIDwvcGF0aD4KICAgICAgICAgPC9zdmc+){.octicon
    .octicon-paste} to copy the remote repository URL. [ ![Copy remote
    repository URL
    field](/assets/cb-25662/images/help/repository/copy-remote-repository-url-quick-setup.png)
    ]{.procedural-image-wrapper}

8.  In Terminal, [add the URL for the remote
    repository](/en/github/getting-started-with-github/managing-remote-repositories)
    where your local repository will be pushed.

                  
                   $ git remote add origin
                   
                    <REMOTE_URL>
                   
                   # Sets the new remote
        $ git remote -v
        # Verifies the new remote URL
                  
                 

9.  [Push the
    changes](/en/github/getting-started-with-github/pushing-commits-to-a-remote-repository)
    in your local repository to GitHub.com.

                  
                   $ git push -u origin main
        # Pushes the changes in your local repository up to the remote repository you specified as the origin
                  
                 
:::

::: {.extended-markdown .windows}
1.  [Create a new repository](/en/articles/creating-a-new-repository) on
    GitHub.com. To avoid errors, do not initialize the new repository
    with *README* , license, or `           gitignore          ` files.
    You can add these files after your project has been pushed to
    GitHub. [ ![Create New Repository
    drop-down](/assets/cb-11427/images/help/repository/repo-create.png)
    ]{.procedural-image-wrapper}

2.  Open [ Terminal ]{.platform-mac} [ Terminal ]{.platform-linux} [ Git
    Bash ]{.platform-windows} .

3.  Change the current working directory to your local project.

4.  Initialize the local directory as a Git repository.

                  
                   $ git init -b main
                  
                 

5.  Add the files in your new local repository. This stages them for the
    first commit.

                  
                   $ git add .
        # Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD
                   
                    YOUR-FILE
                   
                   '.
                  
                 

6.  Commit the files that you\'ve staged in your local repository.

                  
                   $ git commit -m "First commit"
        # Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
                  
                 

7.  At the top of your repository on GitHub.com\'s Quick Setup page,
    click
    ![](data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld2JveD0iMCAwIDE2IDE2IiBjbGFzcz0ib2N0aWNvbiBvY3RpY29uLXBhc3RlIiBhcmlhLWxhYmVsPSJUaGUgY29weSB0byBjbGlwYm9hcmQgaWNvbiIgcm9sZT0iaW1nIj4KICAgICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTUuNzUgMWEuNzUuNzUgMCAwMC0uNzUuNzV2M2MwIC40MTQuMzM2Ljc1Ljc1Ljc1aDQuNWEuNzUuNzUgMCAwMC43NS0uNzV2LTNhLjc1Ljc1IDAgMDAtLjc1LS43NWgtNC41em0uNzUgM1YyLjVoM1Y0aC0zem0tMi44NzQtLjQ2N2EuNzUuNzUgMCAwMC0uNzUyLTEuMjk4QTEuNzUgMS43NSAwIDAwMiAzLjc1djkuNWMwIC45NjYuNzg0IDEuNzUgMS43NSAxLjc1aDguNUExLjc1IDEuNzUgMCAwMDE0IDEzLjI1di05LjVhMS43NSAxLjc1IDAgMDAtLjg3NC0xLjUxNS43NS43NSAwIDEwLS43NTIgMS4yOTguMjUuMjUgMCAwMS4xMjYuMjE3djkuNWEuMjUuMjUgMCAwMS0uMjUuMjVoLTguNWEuMjUuMjUgMCAwMS0uMjUtLjI1di05LjVhLjI1LjI1IDAgMDEuMTI2LS4yMTd6Ij4KICAgICAgICAgIDwvcGF0aD4KICAgICAgICAgPC9zdmc+){.octicon
    .octicon-paste} to copy the remote repository URL. [ ![Copy remote
    repository URL
    field](/assets/cb-25662/images/help/repository/copy-remote-repository-url-quick-setup.png)
    ]{.procedural-image-wrapper}

8.  In the Command prompt, [add the URL for the remote
    repository](/en/github/getting-started-with-github/managing-remote-repositories)
    where your local repository will be pushed.

                  
                   $ git remote add origin
                   
                    <REMOTE_URL>
                   
                   # Sets the new remote
        $ git remote -v
        # Verifies the new remote URL
                  
                 

9.  [Push the
    changes](/en/github/getting-started-with-github/pushing-commits-to-a-remote-repository)
    in your local repository to GitHub.com.

                  
                   $ git push origin main
        # Pushes the changes in your local repository up to the remote repository you specified as the origin
                  
                 
:::

::: {.extended-markdown .linux}
1.  [Create a new repository](/en/articles/creating-a-new-repository) on
    GitHub.com. To avoid errors, do not initialize the new repository
    with *README* , license, or `           gitignore          ` files.
    You can add these files after your project has been pushed to
    GitHub. [ ![Create New Repository
    drop-down](/assets/cb-11427/images/help/repository/repo-create.png)
    ]{.procedural-image-wrapper}

2.  Open [ Terminal ]{.platform-mac} [ Terminal ]{.platform-linux} [ Git
    Bash ]{.platform-windows} .

3.  Change the current working directory to your local project.

4.  Initialize the local directory as a Git repository.

                  
                   $ git init -b main
                  
                 

5.  Add the files in your new local repository. This stages them for the
    first commit.

                  
                   $ git add .
        # Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD
                   
                    YOUR-FILE
                   
                   '.
                  
                 

6.  Commit the files that you\'ve staged in your local repository.

                  
                   $ git commit -m "First commit"
        # Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
                  
                 

7.  At the top of your repository on GitHub.com\'s Quick Setup page,
    click
    ![](data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld2JveD0iMCAwIDE2IDE2IiBjbGFzcz0ib2N0aWNvbiBvY3RpY29uLXBhc3RlIiBhcmlhLWxhYmVsPSJUaGUgY29weSB0byBjbGlwYm9hcmQgaWNvbiIgcm9sZT0iaW1nIj4KICAgICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTUuNzUgMWEuNzUuNzUgMCAwMC0uNzUuNzV2M2MwIC40MTQuMzM2Ljc1Ljc1Ljc1aDQuNWEuNzUuNzUgMCAwMC43NS0uNzV2LTNhLjc1Ljc1IDAgMDAtLjc1LS43NWgtNC41em0uNzUgM1YyLjVoM1Y0aC0zem0tMi44NzQtLjQ2N2EuNzUuNzUgMCAwMC0uNzUyLTEuMjk4QTEuNzUgMS43NSAwIDAwMiAzLjc1djkuNWMwIC45NjYuNzg0IDEuNzUgMS43NSAxLjc1aDguNUExLjc1IDEuNzUgMCAwMDE0IDEzLjI1di05LjVhMS43NSAxLjc1IDAgMDAtLjg3NC0xLjUxNS43NS43NSAwIDEwLS43NTIgMS4yOTguMjUuMjUgMCAwMS4xMjYuMjE3djkuNWEuMjUuMjUgMCAwMS0uMjUuMjVoLTguNWEuMjUuMjUgMCAwMS0uMjUtLjI1di05LjVhLjI1LjI1IDAgMDEuMTI2LS4yMTd6Ij4KICAgICAgICAgIDwvcGF0aD4KICAgICAgICAgPC9zdmc+){.octicon
    .octicon-paste} to copy the remote repository URL. [ ![Copy remote
    repository URL
    field](/assets/cb-25662/images/help/repository/copy-remote-repository-url-quick-setup.png)
    ]{.procedural-image-wrapper}

8.  In Terminal, [add the URL for the remote
    repository](/en/github/getting-started-with-github/managing-remote-repositories)
    where your local repository will be pushed.

                  
                   $ git remote add origin
                   
                    <REMOTE_URL>
                   
                   # Sets the new remote
        $ git remote -v
        # Verifies the new remote URL
                  
                 

9.  [Push the
    changes](/en/github/getting-started-with-github/pushing-commits-to-a-remote-repository)
    in your local repository to GitHub.com.

                  
                   $ git push origin main
        # Pushes the changes in your local repository up to the remote repository you specified as the origin
                  
                 
:::

## [![](data:image/svg+xml;base64,PHN2ZyBhcmlhLWhpZGRlbiByb2xlPSJpbWciIGNsYXNzPSJvY3RpY29uLWxpbmsiIHZpZXdib3g9IjAgMCAxNiAxNiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2IiBmaWxsPSJjdXJyZW50Q29sb3IiIHN0eWxlPSJkaXNwbGF5OmlubGluZS1ibG9jazt1c2VyLXNlbGVjdDpub25lO3ZlcnRpY2FsLWFsaWduOm1pZGRsZSI+CiAgICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTcuNzc1IDMuMjc1YS43NS43NSAwIDAwMS4wNiAxLjA2bDEuMjUtMS4yNWEyIDIgMCAxMTIuODMgMi44M2wtMi41IDIuNWEyIDIgMCAwMS0yLjgzIDAgLjc1Ljc1IDAgMDAtMS4wNiAxLjA2IDMuNSAzLjUgMCAwMDQuOTUgMGwyLjUtMi41YTMuNSAzLjUgMCAwMC00Ljk1LTQuOTVsLTEuMjUgMS4yNXptLTQuNjkgOS42NGEyIDIgMCAwMTAtMi44M2wyLjUtMi41YTIgMiAwIDAxMi44MyAwIC43NS43NSAwIDAwMS4wNi0xLjA2IDMuNSAzLjUgMCAwMC00Ljk1IDBsLTIuNSAyLjVhMy41IDMuNSAwIDAwNC45NSA0Ljk1bDEuMjUtMS4yNWEuNzUuNzUgMCAwMC0xLjA2LTEuMDZsLTEuMjUgMS4yNWEyIDIgMCAwMS0yLjgzIDB6Ij4KICAgICAgICAgPC9wYXRoPgogICAgICAgIDwvc3ZnPg==){.octicon-link}](#further-reading){.doctocat-link} Further reading

-   \" [Adding a file to a
    repository](/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository#adding-a-file-to-a-repository-using-the-command-line)
    \"
:::
:::
:::
:::
:::
:::
