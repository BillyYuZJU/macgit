hello world
what second line







Last login: Tue Nov 27 14:01:11 on ttys000
-bash: alias: added: not found
-bash: alias: by: not found
-bash: alias: Anaconda3: not found
-bash: alias: 5.3.0: not found
-bash: alias: installer: not found
BillydeMacBook-Pro:~ BillyYu$ ls
Applications		Polyspace_Workspace	matlab_crash_dump.505-1
Desktop			Public			matlab_crash_dump.594-1
Documents		PycharmProjects		matlab_crash_dump.634-1
Downloads		SteamLibrary		matlab_crash_dump.770-1
Library			dart			matlab_crash_dump.865-1
Movies			gazebo_plugin_tutorial	model_editor_models
Music			gazebo_tu1		mygit
Pictures		matlab_crash_dump.414-1	请先阅读.pdf
BillydeMacBook-Pro:~ BillyYu$ cd mygit/
BillydeMacBook-Pro:mygit BillyYu$ ls
BillydeMacBook-Pro:mygit BillyYu$ ssh-keygen -t rsa -C "657868404@qq.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/BillyYu/.ssh/id_rsa): ls
Enter passphrase (empty for no passphrase): 

BillydeMacBook-Pro:mygit BillyYu$ ssh-keygen -t rsa -C "657868404@qq.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/BillyYu/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /Users/BillyYu/.ssh/id_rsa.
Your public key has been saved in /Users/BillyYu/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:v3PcFsH9giXHV15wLyGDCm3uPzlskCiG7EV1NBsLzpU 657868404@qq.com
The key's randomart image is:
+---[RSA 2048]----+
|      .o=. .o o..|
|     oooE=.  o o+|
|     .o=o.   o.o+|
|    .   o   . *.+|
| . o   oS.   = o.|
|  o + . +.  . o .|
| . o .   +.o . o |
|  .       O.o o  |
|         ..= .   |
+----[SHA256]-----+
BillydeMacBook-Pro:mygit BillyYu$ ls
BillydeMacBook-Pro:mygit BillyYu$ cd ..
BillydeMacBook-Pro:~ BillyYu$ ls
Applications		Polyspace_Workspace	matlab_crash_dump.505-1
Desktop			Public			matlab_crash_dump.594-1
Documents		PycharmProjects		matlab_crash_dump.634-1
Downloads		SteamLibrary		matlab_crash_dump.770-1
Library			dart			matlab_crash_dump.865-1
Movies			gazebo_plugin_tutorial	model_editor_models
Music			gazebo_tu1		mygit
Pictures		matlab_crash_dump.414-1	请先阅读.pdf
BillydeMacBook-Pro:~ BillyYu$ cd .ssh
BillydeMacBook-Pro:.ssh BillyYu$ cd ..
BillydeMacBook-Pro:~ BillyYu$ la
-bash: la: command not found
BillydeMacBook-Pro:~ BillyYu$ cd .ssh
BillydeMacBook-Pro:.ssh BillyYu$ ls
id_rsa		id_rsa.pub	known_hosts
BillydeMacBook-Pro:.ssh BillyYu$ cd id_rsa
-bash: cd: id_rsa: Not a directory
BillydeMacBook-Pro:.ssh BillyYu$ vi id_rsa
BillydeMacBook-Pro:.ssh BillyYu$ vi id_rsa.pub 
BillydeMacBook-Pro:.ssh BillyYu$ cd ~
BillydeMacBook-Pro:~ BillyYu$ cd mygit/
BillydeMacBook-Pro:mygit BillyYu$ ls
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
BillydeMacBook-Pro:mygit BillyYu$ vi README.md
BillydeMacBook-Pro:mygit BillyYu$ ls
BillydeMacBook-Pro:mygit BillyYu$ gedit README.md
Password:
Sorry, try again.
Password:
The file /Users/BillyYu/mygit/README.md does not exist.
BillydeMacBook-Pro:mygit BillyYu$ vi a.md
BillydeMacBook-Pro:mygit BillyYu$ ls
a.md
BillydeMacBook-Pro:mygit BillyYu$ cat a.md 
hello world
BillydeMacBook-Pro:mygit BillyYu$ git add a.md 
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   a.md

BillydeMacBook-Pro:mygit BillyYu$ git commit -m "first commit"
[master (root-commit) 21ca1b4] first commit
 Committer: Billy Yu <BillyYu@BillydeMacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 a.md
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master
nothing to commit, working tree clean
BillydeMacBook-Pro:mygit BillyYu$ git remote add origin https://github.com/BillyYuZJU/macgit.git
BillydeMacBook-Pro:mygit BillyYu$ git push -u origin master
Username for 'https://github.com': BillyYuZJU
Password for 'https://BillyYuZJU@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 228 bytes | 228.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/BillyYuZJU/macgit/pull/new/master
remote: 
To https://github.com/BillyYuZJU/macgit.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
BillydeMacBook-Pro:mygit BillyYu$ vi a.md 
BillydeMacBook-Pro:mygit BillyYu$ git push origin master
Everything up-to-date
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   a.md

no changes added to commit (use "git add" and/or "git commit -a")
BillydeMacBook-Pro:mygit BillyYu$ git add a.md 
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   a.md

BillydeMacBook-Pro:mygit BillyYu$ git commit a.md
Aborting commit due to empty commit message.
BillydeMacBook-Pro:mygit BillyYu$ git commit -m a.md
[master b4f62a0] a.md
 Committer: Billy Yu <BillyYu@BillydeMacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
BillydeMacBook-Pro:mygit BillyYu$ git push origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 272 bytes | 272.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/BillyYuZJU/macgit.git
   21ca1b4..b4f62a0  master -> master
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
BillydeMacBook-Pro:mygit BillyYu$ vi a.md 
BillydeMacBook-Pro:mygit BillyYu$ ls
a.md
BillydeMacBook-Pro:mygit BillyYu$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
BillydeMacBook-Pro:mygit BillyYu$ 

