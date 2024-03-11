# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web
$ git init
Initialized empty Git repository in C:/Users/ferna/Documents/Pemrograman Web/.git/

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web (master)
$ git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --[no-]verbose    be more verbose
    -q, --[no-]quiet      be more quiet
    --[no-]progress       force progress reporting
    --[no-]reject-shallow don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --checkout            opposite of --no-checkout
    --[no-]bare           create a bare repository
    --[no-]mirror         create a mirror repository (implies bare)
    -l, --[no-]local      to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    --hardlinks           opposite of --no-hardlinks
    -s, --[no-]shared     setup as shared repository
    --[no-]recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --[no-]recursive ...  alias of --recurse-submodules
    -j, --[no-]jobs <n>   number of submodules cloned in parallel
    --[no-]template <template-directory>
                          directory from which templates will be used
    --[no-]reference <repo>
                          reference repository
    --[no-]reference-if-able <repo>
                          reference repository
    --[no-]dissociate     use --reference only while cloning
    -o, --[no-]origin <name>
                          use <name> instead of 'origin' to track upstream
    -b, --[no-]branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --[no-]upload-pack <path>
                          path to git-upload-pack on the remote
    --[no-]depth <depth>  create a shallow clone of that depth
    --[no-]shallow-since <time>
                          create a shallow clone since a specific time
    --[no-]shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --[no-]single-branch  clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --tags                opposite of --no-tags
    --[no-]shallow-submodules
                          any cloned submodules will be shallow
    --[no-]separate-git-dir <gitdir>
                          separate git dir from working tree
    --[no-]ref-format <format>
                          specify the reference format to use
    -c, --[no-]config <key=value>
                          set config inside the new repository
    --[no-]server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --[no-]filter <args>  object filtering
    --[no-]also-filter-submodules
                          apply partial clone filters to submodules
    --[no-]remote-submodules
                          any cloned submodules will use their remote-tracking branch
    --[no-]sparse         initialize sparse-checkout file to include only files at root
    --[no-]bundle-uri <uri>
                          a URI for downloading bundles before fetching from origin remote


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web (master)
$ git clone https://github.com/LeyzarCae/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web (master)
$ cd belajarGIT

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-git

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git commit -m "Tugas-git"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ferna@DESKTOP-SAV99CG.(none)')

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ ^C

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ ^[[200~git config --global user.email "you@example.com"
bash: $'\E[200~git': command not found

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git config --global user.email "Leyzarfwarouw@gmail.com"

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git config --global user.email "leyzarfwarouw@gmail.com"

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git config --global user.name "LeyzarCae"

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git commit -m "Tugas-git"
[Tugas-git 91d94e5] Tugas-git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-git
Updating 88498aa..91d94e5
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 289 bytes | 289.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/LeyzarCae/belajarGIT
   88498aa..91d94e5  main -> main

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-html

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git commit -m "Tugas-html"
[Tugas-html cab73cc] Tugas-html
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Everything up-to-date

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-html
Updating 91d94e5..cab73cc
Fast-forward
 Tugas-html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/LeyzarCae/belajarGIT
   91d94e5..cab73cc  main -> main

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-css

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-html)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git commit -m "Tugas-css"
[Tugas-css 0878082] Tugas-css
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-css
Updating cab73cc..0878082
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/LeyzarCae/belajarGIT
   cab73cc..0878082  main -> main

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-js

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git commit -m "Tugas-js"
[Tugas-js 91735f0] Tugas-js
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git merge Tugas-js
Already up to date.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Everything up-to-date

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-js
Updating 0878082..91735f0
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 279 bytes | 279.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/LeyzarCae/belajarGIT
   0878082..91735f0  main -> main

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-midProject

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject
fatal: pathspec 'Tugas-midProject' did not match any files

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git commit -m "Tugas-midProject"
[Tugas-midProject e282dc7] Tugas-midProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git merge Tugas-midProject
Already up to date.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Everything up-to-date

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-midProject
Updating 91735f0..e282dc7
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 295 bytes | 295.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/LeyzarCae/belajarGIT
   91735f0..e282dc7  main -> main

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-php

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git commit -m "Tugas-php"
[Tugas-php e6301f5] Tugas-php
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Everything up-to-date

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-php
Updating e282dc7..e6301f5
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/LeyzarCae/belajarGIT
   e282dc7..e6301f5  main -> main

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-finalProject

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git commit -m "Tugas-finalProject"
[Tugas-finalProject e4f57df] Tugas-finalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-finalProject
Updating e6301f5..e4f57df
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/LeyzarCae/belajarGIT
   e6301f5..e4f57df  main -> main

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/LeyzarCae/belajarGIT
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$ ^C

ferna@DESKTOP-SAV99CG MINGW64 ~/Documents/Pemrograman Web/belajarGIT (main)
$
