# Git-Learning

# Bundle 1


The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
OTF:GitLearning pothin_otf$ git init
Reinitialized existing Git repository in /Users/pothin_otf/Desktop/Playwright/LambdaTestWorkSpace/GitLearning/.git/
OTF:GitLearning pothin_otf$ git status
On branch main

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file:   .gitignore
new file:   .idea/.gitignore
new file:   .idea/misc.xml
new file:   .idea/modules.xml
new file:   .idea/vcs.xml
new file:   GitLearning.iml
new file:   src/Main.java

OTF:GitLearning pothin_otf$ git branch
OTF:GitLearning pothin_otf$ git branch -m main master
OTF:GitLearning pothin_otf$ git branch
OTF:GitLearning pothin_otf$ git branch -m master main
OTF:GitLearning pothin_otf$ git status
On branch main

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file:   .gitignore
new file:   .idea/.gitignore
new file:   .idea/misc.xml
new file:   .idea/modules.xml
new file:   .idea/vcs.xml
new file:   GitLearning.iml
new file:   src/Main.java

OTF:GitLearning pothin_otf$ git add .
OTF:GitLearning pothin_otf$ git commit -m "renamed master to main"
[main (root-commit) 0539a15] renamed master to main
7 files changed, 79 insertions(+)
create mode 100644 .gitignore
create mode 100644 .idea/.gitignore
create mode 100644 .idea/misc.xml
create mode 100644 .idea/modules.xml
create mode 100644 .idea/vcs.xml
create mode 100644 GitLearning.iml
create mode 100644 src/Main.java
OTF:GitLearning pothin_otf$ git remote add git@github.com:Pothin-Neza/Git-Learning.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

OTF:GitLearning pothin_otf$ git remote add origin OTF:GitLearning pothin_otf$ git remote add git@github.com:Pothin-Neza/Git-Learning.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

OTF:GitLearning pothin_otf$ usage: git remote add [<options>] <name> <url>
bash: syntax error near unexpected token `<'
OTF:GitLearning pothin_otf$ 
OTF:GitLearning pothin_otf$     -f, --fetch           fetch the remote branches
bash: -f,: command not found
OTF:GitLearning pothin_otf$     --tags                import all tags and associated objects when fetching
bash: --tags: command not found
OTF:GitLearning pothin_otf$                           or do not fetch any tag at all (--no-tags)
bash: syntax error near unexpected token `('
OTF:GitLearning pothin_otf$     -t, --track <branch>  branch(es) to track
bash: syntax error near unexpected token `('
OTF:GitLearning pothin_otf$     -m, --master <branch>
bash: syntax error near unexpected token `newline'
OTF:GitLearning pothin_otf$                           master branch
bash: master: command not found
OTF:GitLearning pothin_otf$     --mirror[=(push|fetch)]
bash: syntax error near unexpected token `push'
OTF:GitLearning pothin_otf$                           set up remote as a mirror to push to or fetch from
OTF:GitLearning pothin_otf$ git remote add origin OTF:GitLearning pothin_otf$ git remote add git@github.com:Pothin-Neza/Git-Learning.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

OTF:GitLearning pothin_otf$ usage: git remote add [<options>] <name> <url>
bash: syntax error near unexpected token `<'
OTF:GitLearning pothin_otf$ 
OTF:GitLearning pothin_otf$     -f, --fetch           fetch the remote branches
bash: -f,: command not found
OTF:GitLearning pothin_otf$     --tags                import all tags and associated objects when fetching
bash: --tags: command not found
OTF:GitLearning pothin_otf$                           or do not fetch any tag at all (--no-tags)
bash: syntax error near unexpected token `('
OTF:GitLearning pothin_otf$     -t, --track <branch>  branch(es) to track
bash: syntax error near unexpected token `('
OTF:GitLearning pothin_otf$     -m, --master <branch>
bash: syntax error near unexpected token `newline'
OTF:GitLearning pothin_otf$                           master branch
bash: master: command not found
OTF:GitLearning pothin_otf$     --mirror[=(push|fetch)]
bash: syntax error near unexpected token `push'
OTF:GitLearning pothin_otf$                           set up remote as a mirror to push to or fetch from
OTF:GitLearning pothin_otf$ git remote add origin git@github.com:Pothin-Neza/Git-Learning.git
OTF:GitLearning pothin_otf$ git remote -v
origin  git@github.com:Pothin-Neza/Git-Learning.git (fetch)
origin  git@github.com:Pothin-Neza/Git-Learning.git (push)
OTF:GitLearning pothin_otf$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

OTF:GitLearning pothin_otf$     git push --set-upstream origin main
^[[CTo github.com:Pothin-Neza/Git-Learning.git
! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:Pothin-Neza/Git-Learning.git'
hint: Updates were rejected because the remote contains work that you do       
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
OTF:GitLearning pothin_otf$ git push     git push --set-upstream origin main
error: src refspec push does not match any
error: src refspec origin does not match any
error: failed to push some refs to 'git'
OTF:GitLearning pothin_otf$ git push --set-upstream origin main                
To github.com:Pothin-Neza/Git-Learning.git
! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:Pothin-Neza/Git-Learning.git'
hint: Updates were rejected because the remote contains work that you do       
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
OTF:GitLearning pothin_otf$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 865 bytes | 108.00 KiB/s, done.
From github.com:Pothin-Neza/Git-Learning
* [new branch]      main       -> origin/main
  There is no tracking information for the current branch.
  Please specify which branch you want to merge with.
  See git-pull(1) for details.

  git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

OTF:GitLearning pothin_otf$ git pull origin main
From github.com:Pothin-Neza/Git-Learning
* branch            main       -> FETCH_HEAD
  hint: You have divergent branches and need to specify how to reconcile them.
  hint: You can do so by running one of the following commands sometime before
  hint: your next pull:
  hint:
  hint:   git config pull.rebase false  # merge
  hint:   git config pull.rebase true   # rebase
  hint:   git config pull.ff only       # fast-forward only
  hint:
  hint: You can replace "git config" with "git config --global" to set a default
  hint: preference for all repositories. You can also pass --rebase, --no-rebase,
  hint: or --ff-only on the command line to override the configured default per
  hint: invocation.
  fatal: Need to specify how to reconcile divergent branches.
  OTF:GitLearning pothin_otf$ git branch --set-upstream-to=origin/main main
  branch 'main' set up to track 'origin/main'.
  OTF:GitLearning pothin_otf$ git pull
  hint: You have divergent branches and need to specify how to reconcile them.
  hint: You can do so by running one of the following commands sometime before
  hint: your next pull:
  hint:
  hint:   git config pull.rebase false  # merge
  hint:   git config pull.rebase true   # rebase
  hint:   git config pull.ff only       # fast-forward only
  hint:
  hint: You can replace "git config" with "git config --global" to set a default
  hint: preference for all repositories. You can also pass --rebase, --no-rebase,
  hint: or --ff-only on the command line to override the configured default per
  hint: invocation.
  fatal: Need to specify how to reconcile divergent branches.
  OTF:GitLearning pothin_otf$ git config pull.rebase false
  OTF:GitLearning pothin_otf$ git pull origin main --allow-unrelated-histories
  From github.com:Pothin-Neza/Git-Learning
* branch            main       -> FETCH_HEAD

Merge made by the 'ort' strategy.
README.md | 1 +
1 file changed, 1 insertion(+)
create mode 100644 README.md
OTF:GitLearning pothin_otf$ git push
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (13/13), 2.22 KiB | 226.00 KiB/s, done.
Total 13 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To github.com:Pothin-Neza/Git-Learning.git
1430ad0..ef531f1  main -> main
OTF:GitLearning pothin_otf$ git checkout -b dev
Switched to a new branch 'dev'
OTF:GitLearning pothin_otf$ git branch
* dev
  main
  OTF:GitLearning pothin_otf$ git checkout -b test
  Switched to a new branch 'test'
  OTF:GitLearning pothin_otf$ git branch
  dev
  main
* test
  OTF:GitLearning pothin_otf$ git checkout dev
  Switched to branch 'dev'
  OTF:GitLearning pothin_otf$ git branch -d test
  Deleted branch test (was ef531f1).
  OTF:GitLearning pothin_otf$ git branch
* dev
  main
  OTF:GitLearning pothin_otf$ git status
  On branch dev
  Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
  new file:   src/index.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   src/index.html

OTF:GitLearning pothin_otf$ git stash
Saved working directory and index state WIP on dev: ef531f1 Merge branch 'main' of github.com:Pothin-Neza/Git-Learning
OTF:GitLearning pothin_otf$ git branch
* dev
  main
  OTF:GitLearning pothin_otf$ git checkout main
  Switched to branch 'main'
  Your branch is up to date with 'origin/main'.
  OTF:GitLearning pothin_otf$ git checkout dev
  Switched to branch 'dev'
  OTF:GitLearning pothin_otf$ git status
  On branch dev
  nothing to commit, working tree clean
  OTF:GitLearning pothin_otf$ git status
  On branch dev
  nothing to commit, working tree clean
  OTF:GitLearning pothin_otf$
  OTF:GitLearning pothin_otf$ git status
  On branch dev
  Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
  new file:   src/about.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   src/about.html

OTF:GitLearning pothin_otf$ git stash
Saved working directory and index state WIP on dev: ef531f1 Merge branch 'main' of github.com:Pothin-Neza/Git-Learning
OTF:GitLearning pothin_otf$ git status
On branch dev
nothing to commit, working tree clean
OTF:GitLearning pothin_otf$ git status
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   src/team.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   src/team.html

OTF:GitLearning pothin_otf$ git stash
Saved working directory and index state WIP on dev: ef531f1 Merge branch 'main' of github.com:Pothin-Neza/Git-Learning
OTF:GitLearning pothin_otf$ git log --oneline
ef531f1 (HEAD -> dev, origin/main, main) Merge branch 'main' of github.com:Pothin-Neza/Git-Learning
1430ad0 Initial commit
0539a15 renamed master to main
OTF:GitLearning pothin_otf$ git stash list
stash@{0}: WIP on dev: ef531f1 Merge branch 'main' of github.com:Pothin-Neza/Git-Learning
stash@{1}: WIP on dev: ef531f1 Merge branch 'main' of github.com:Pothin-Neza/Git-Learning
stash@{2}: WIP on dev: ef531f1 Merge branch 'main' of github.com:Pothin-Neza/Git-Learning
OTF:GitLearning pothin_otf$ git stash pop stash@{1}
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   src/about.html

Dropped stash@{1} (ae74da33a16818216d6b33260b5bf651738c60ba)
OTF:GitLearning pothin_otf$ git stash pop stash@{0}
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   src/about.html
new file:   src/team.html

Dropped stash@{0} (dcb1330627ce1aa085f8ba53100edcf11d6758ca)
OTF:GitLearning pothin_otf$ git status
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   src/about.html
new file:   src/team.html

OTF:GitLearning pothin_otf$ git commit -m "stash popped about and team"
[dev f5a0c77] stash popped about and team
2 files changed, 20 insertions(+)
create mode 100644 src/about.html
create mode 100644 src/team.html
OTF:GitLearning pothin_otf$ git stash pop stash@{2}
fatal: log for 'stash' only has 1 entries
OTF:GitLearning pothin_otf$ git stash pop stash@{2}
fatal: log for 'stash' only has 1 entries
OTF:GitLearning pothin_otf$ git stash pop
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   src/index.html

Dropped refs/stash@{0} (eac3fb093d41e060f7c7f4981ae0e7a9ceb6e2aa)
OTF:GitLearning pothin_otf$ git status
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   src/index.html

OTF:GitLearning pothin_otf$ git clean -f index.html
OTF:GitLearning pothin_otf$ git reset --hard
HEAD is now at f5a0c77 stash popped about and team
OTF:GitLearning pothin_otf$ 

# Bundle 2

OTF:GitLearning pothin_otf$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
OTF:GitLearning pothin_otf$ git branch
dev
* ft/bundle-2
  main
  OTF:GitLearning pothin_otf$ git status
  On branch ft/bundle-2
  Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
  deleted:    src/Main.java
  new file:   src/services.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   README.md
modified:   src/services.html

OTF:GitLearning pothin_otf$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
add
OTF:GitLearning pothin_otf$ git add .
OTF:GitLearning pothin_otf$ git commit -m "services page"
[ft/bundle-2 400ea4e] services page
3 files changed, 374 insertions(+), 16 deletions(-)
delete mode 100644 src/Main.java
create mode 100644 src/services.html
OTF:GitLearning pothin_otf$ git push origin main
Everything up-to-date
OTF:GitLearning pothin_otf$ git push origin ft/bundle-2
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 3.67 KiB | 1.83 MiB/s, done.
Total 10 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Pothin-Neza/Git-Learning/pull/new/ft/bundle-2
remote:
To github.com:Pothin-Neza/Git-Learning.git
* [new branch]      ft/bundle-2 -> ft/bundle-2

# bundle 3

