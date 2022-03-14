GOSTO de ajudar os outros c/ programação (principalmente com POO, Orientada é gostosinho de programar)

Tenho essa segunda conta também: [Alkovalski](https://github.com/Alkovalski), mas não uso muito ela não (ela tem um joguinho de [batalha naval](https://alkovalski.github.io/naval/batalha-naval.html) maneirão)

Tb tenho que organizar meus repositórios, ta td uma bagunça

Odeio quando o git nn deixa eu fazer um commit DIRETO na branch main >:(
<!--
Colinha dos comandos do git hihhiihihhihihihi

https://devconnected.com/how-to-push-git-branch-to-remote/
https://stackoverflow.com/questions/12799719/how-to-upload-a-project-to-github

Push Branch To Remote

In order to push a Git branch to remote, you need to execute the “git push” command and specify the remote as well as the branch name to be pushed.

$ git push <remote> <branch>

-----------------------------------------------
For example, if you need to push a branch named “feature” to the “origin” remote, you would execute the following query

$ git push origin feature

-----------------------------------------------
If you are not already on the branch that you want to push, you can execute the “git checkout” command to switch to your branch.

If your upstream branch is not already created, you will need to create it by running the “git push” command with the “-u” option for upstream.
git push upstream branch to remote

$ git push -u origin feature

Congratulations, you have successfully pushed your branch to your remote!
-----------------------------------------------

>>>>> Push Branch to Another Branch <<<<<

In some cases, you may want to push your changes to another branch on the remote repository.

In order to push your branch to another remote branch, use the “git push” command and specify the remote name, the name of your local branch as the name of the remote branch.

$ git push <remote> <local_branch>:<remote_name>

As an example, let’s say that you have created a local branch named “my-feature”.

$ git branch

  master
* my-feature
  feature

However, you want to push your changes to the remote branch named “feature” on your repository.

In order to push your branch to the “feature” branch, you would execute the following command

$ git push origin my-feature:feature

Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 513 bytes | 513.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SCHKN/repo.git
   b1c4c91..9ae0aa6  my-feature -> feature

(no meu caso, $ git push origin master:main )

In order to push your branch to another branch, you may need to merge the remote branch to your current local branch.

In order to be merged, the tip of the remote branch cannot be behind the branch you are trying to push.

Before pushing, make sure to pull the changes from the remote branch and integrate them with your current local branch.

$ git pull

$ git checkout my-feature

$ git merge origin/feature

$ git push origin my-feature:feature

    Note : when merging the remote branch, you are merging your local branch with the upstream branch of your local repository.

Congratulations, you pushed your branch to another branch on your repository!
Push Branch to Another Repository

In order to push a branch to another repository, you need to execute the “git push” command, and specify the correct remote name as well as the branch to be pushed.

$ git push <remote> <branch>

In order to see the remotes defined in your repository, you have to execute the “git remote” command with the “-v” option for “verbose”.

$ git remote -v

origin  https://github.com/user/repo.git (fetch)
origin  https://github.com/user/repo.git (push)
custom  https://github.com/user/custom.git (fetch)
custom  https://github.com/user/custom.git (push)

In the previous examples, we pushed our branch to the “origin” remote but we can choose to publish it to the “custom” remote if we want.

$ git push custom feature

Awesome, you pushed your branch to another remote repository!
Troubleshooting

In some cases, you may run into errors while trying to push a Git branch to a remote.
Failed to push some refs
git push branch troubleshooting

The error message states that the a pushed branch tip is behind its remote (references are behind)

In order to fix this, you need first to pull the recent changes from your remote branches with the “git pull” command.

$ git pull

When pulling the changes, you may run into merge conflicts, run the conflicts and perform a commit again with your results.

Now that the files are merged, you may try to push your branch to the remote again.

$ git push origin feature

Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 513 bytes | 513.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SCHKN/repo.git
   b1c4c91..9ae0aa6  feature -> feature

Conclusion

In this tutorial, you learnt how you can push a Git branch to a remote with the “git push” command.

You learnt that you can easily specify your branch and your remote if you want to send your changes to other repositories.



======================================================================================
Here is how you would do it in Windows:

    If you don't have Git installed, see this article on how to set it up.

    Open up a Windows command prompt.

    Change into the directory where your source code is located in the command prompt.

    First, create a new repository in this directory git init. This will say "Initialized empty git repository in ....git" (... is the path).

    Now you need to tell Git about your files by adding them to your repository. Do this with git add filename. If you want to add all your files, you can do git add .

    Now that you have added your files and made your changes, you need to commit your changes so Git can track them. Type git commit -m "adding files". -m lets you add the commit message in line.

So far, the above steps is what you would do even if you were not using GitHub. They are the normal steps to start a Git repository. Remember that Git is distributed (decentralized), meaning you don't need to have a "central server" (or even a network connection), to use Git.

Now you want to push the changes to your Git repository hosted with GitHub. You do this by telling Git to add a remote location, and you do that with this command:

$ git remote add origin https://github.com/yourusername/your-repo-name.git

*Note: your-repo-name should be created in GitHub before you do a git remote add origin ...

Once you have done that, Git now knows about your remote repository. You can then tell it to push (which is "upload") your committed files:

$ git push -u origin master
(caso vc queria só fazer upload no trabalho remoto, sem ligar pra nada, colocar -f pra fazer upload, tipo quando eu queria colocar o minimo que eu tinha no repo do guitarino 2)

### Hi there 👋
**Kovalski-rgb/kovalski-rgb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
Achei bunitu vou deixar td aqui
-->
