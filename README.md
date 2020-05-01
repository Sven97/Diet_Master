# Diet Master - CPS 4951 Capstone Project

A web-based application intend to make intelligent recipe recommendation and help the users to balance the diets.

## Notice before Development

### Use `dev` branch for development

Please make all the modification in branch `dev`.

Do NOT merge to the `master` branch before code review 

```
# switch to dev brach
git switch dev
```

### `git pull` before starting and committing

Don't forget to execute `git pull` in the `dev` branch before starting coding and committing to the GitHub.  

```
# go to the dev branch
git checkout dev
# sync remote repository
git pull
```

### Resolve `git merge conflict`

There are multiple approaches to resolve merge conflicts. If you are using command line, `git mergetool` and `git meld` are what I can suggest on resolving merge conflicts.

If you are using IDEs from JetBrains such as PyCharm. Please follows the following steps to resolve the merge conflicts which need to be manually fixed.

1. VCS - Git - Resolve Conflicts...
2. Choose among Accept Yours, Accept Theirs and Merge (manually fix, highly recommended)
3. The popup windows "Merge Revisions" provides 3 columns indicates "Local Changes", "Result" and "Changes from Server" from the left to the right. You can make change decisions accordingly.
4. Conflicts resolved and push successfully!

## Configuration and Installation

1. Make sure [Git](https://git-scm.com/downloads) is installed in your computer.

2. Clone the repository.

   ```
   git clone https://github.com/Sven97/Diet_Master.git
   ```

3. Set up the `Django` environment following [Setup Manual](docs/setup.md)

4. After the Python environment is activated, you can run the server. 
   ```
   (venv) > python manage.py runserver
   ```

5. The website should work properly at [http://127.0.0.1:8000](http://127.0.0.1:8000).
