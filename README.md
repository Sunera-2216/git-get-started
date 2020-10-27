## Instructions to Get Started

1. On the [GitHub page for this repository](https://github.com/Sunera-2216/github-get-started.git), click on the Button "Fork".

   ![fork image](https://help.github.com/assets/images/help/repository/fork_button.jpg)

2. Clone _your forked repository_ to your computer:

   Click on the green button and copy the HTTPS url.

   ![code ui](https://docs.github.com/assets/images/help/repository/code-button.png)

    For clone, run this command inside your terminal/cmd:

    ```bash
    git clone https://github.com/<your-user-name>/github-get-started.git
    ```

    Learn more about [forking](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [cloning a repo](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).


3. On your computer, select the folder of your favourite programming language(if folder doesn't exist of your language, create new folder) and add a source code file.

4. Add the changes to the github with `git add`, `git commit`:

    ```bash
    git add <your-file-name> (Ex :- git add hello_world.c)
    git commit -m "<your-commit-message>" (Ex :- git commit -m "Added C program file")
    ```

5. Push your changes _to your repository_:

    ```bash
    git push origin master
    ```

6. Go to the GitHub page of _your fork_, and make a pull request:

    ![pull request image](https://help.github.com/assets/images/help/pull_requests/choose-base-and-compare-branches.png)

    Read more about pull requests on the [GitHub help pages](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

7. Wait until Zerobot or one of the maintainers merges your pull request. If there are any conflicts, you will get a notification.

8. That's all. You're just completed beginner guide to github. :smiley: :tada: :confetti_ball:
