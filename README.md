ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQCyDAb/xomJha+J9vs+XOunndn9hpqy6VNP2OEjJacxM5Ny5/PLE24TeGO2AId6VAJUaUrtiAxNYtNCIZh2kZrHJjyD1xNr5yW2zupvTTbFr+kTA/GbbL6TTRHyeG2zL94bYOHxOoLL5DFD1R3kG1jT6Avyf9kwrAxXB1XjNDUi8N5DnhdI2N/YtlspoFQHIRU/1yCmFGaNeIDzIP1eBV9waWn6jAXfgFnk/zWfJxrsv9K2k5m5WK1n16WoXalEVOCJ4Q2EZnVmBvz1parBxZOMxKKgeNkrUCVgTjb0f5bNqnWOJjT+XSS3GQQ3bheSFIds/4xUORrPkXcKxHNenNdjdRZVeRdlwFj20fEDmj5vIvPuw75LS0T0gR7TvTKlPqYZ7LE5vSsEoyX2NvqJ/aQ7KgQSxio2mo4YZLNhegRgnv2WAeJ1TetbojCBciIA7PuYXNPpq88IoioC5zwU0Yu2if9ZHbHzNtVXBMb15iRHg1jAfeTn4IOP7AUh4UYCRAevaXnsWXCs73g7nNT6ojXD2X4J+vIOKKc+wlUil7NRc9LPlc1I1dkhaaDq0xz9LM4mYJvC9bB4uZUkNHIhbNBwvm9bcmOJcOOidUOtVulMdSwYHJXiNs4V6+ZezXIzVRavmtXY+/ZVhhV6tH3JvsEpn3iZsIDwQkaC7/d1a/pGQw== websm3@gmail.com
Agent pid 32979

student@PRLAB-8:~$ cd 6015
student@PRLAB-8:~/6015$ vi filealloc.c
student@PRLAB-8:~/6015$ gcc filealloc.c
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 1
Enter starting block: 1
Enter file length: 5
File allocated from block 1 to 5.
Memory Blocks:
0 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 2
Enter file ID: 101
Enter number of blocks: 4
Enter block numbers:
2 3 4 5
Block 2 is already occupied. Indexed allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: Enter file ID: Enter number of blocks: Enter block numbers:
3
Block 3 is already occupied. Linked allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 102
Invalid choice! Try again.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 3
Enter file ID: 102
Enter number of blocks: 3
Enter block numbers:
1 5 7
Block 1 is already occupied. Linked allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: Invalid choice! Try again.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: Invalid choice! Try again.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 4
Exiting program...
student@PRLAB-8:~/6015$ vi pipe.c
student@PRLAB-8:~/6015$ vi pipe.c
student@PRLAB-8:~/6015$ gcc pipe.c
student@PRLAB-8:~/6015$ ./a.out
Child received: Hello from parent!
Parent process finished.
student@PRLAB-8:~/6015$ gcc filealloc.c
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 1
Enter starting block: 0
Enter file length: 5
File allocated from block 0 to 4.
Memory Blocks:
1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: ^C
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 2
Enter file ID: 1
Enter number of blocks: 3
Enter block numbers:
0
1
2
File 1 allocated at index block. Data blocks: 0 1 2 
Memory Blocks:
1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 2
Enter file ID: 1
Enter number of blocks: 3
Enter block numbers:
5 6 7
File 1 allocated at index block. Data blocks: 5 6 7 
Memory Blocks:
1 1 1 0 0 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 1
Enter starting block: 0
Enter file length: 5
Block 0 already occupied. Contiguous allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 2 
Enter file ID: 1
Enter number of blocks: 3
Enter block numbers:
0 1 2
Block 0 is already occupied. Indexed allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: Enter starting block: Enter file length: 2
Block 2 already occupied. Contiguous allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 1
Enter starting block: 3
Enter file length: 5 6 7
Block 5 already occupied. Contiguous allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: Invalid choice! Try again.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: Invalid choice! Try again.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 3
Enter file ID: 1
Enter number of blocks: 3
Enter block numbers:
0
Block 0 is already occupied. Linked allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: ]1
Enter file ID: Enter number of blocks: Enter block numbers:
Segmentation fault (core dumped)
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 3
Enter file ID: 1
Enter number of blocks: 3
Enter block numbers:
0 1 2
File 1 allocated. Blocks: 0 -> 1 -> 2 -> NULL
Memory Blocks:
1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 3
Enter file ID: 1
Enter number of blocks: 3
Enter block numbers:
5
6
7
File 1 allocated. Blocks: 5 -> 6 -> 7 -> NULL
Memory Blocks:
1 1 1 0 0 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 2
Enter file ID: 1
Enter number of blocks: 3
Enter block numbers:
0
Block 0 is already occupied. Indexed allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 1
Enter starting block: 0
Enter file length: 5
Block 0 already occupied. Contiguous allocation failed.

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 4
Exiting program...
student@PRLAB-8:~/6015$ vi filealloc.c
student@PRLAB-8:~/6015$ gcc filealloc.c
^[[A^[[Astudent@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 4
15^C
student@PRLAB-8:~/6015$ vi filealloc.c
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: ^[[A^[[A^[[A^C
student@PRLAB-8:~/6015$ gcc filealloc.c
^[[Astudent@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 4
1Exited Program in
student@PRLAB-8:~/6015$ wq
wq: command not found
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: ^[[A^C
student@PRLAB-8:~/6015$ vi filealloc.c
student@PRLAB-8:~/6015$ gcc filealloc.c
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 4
Exited
student@PRLAB-8:~/6015$ ./a.out

File Allocation Strategies:
1. Contiguous Allocation
2. Indexed Allocation
3. Linked Allocation
4. Exit
Enter your choice: 4 
Exited
student@PRLAB-8:~/6015$ vi filealloc.c
student@PRLAB-8:~/6015$ ls
a.out  bankalgo.c  dlprev.c  filealloc.c  pipe.c  piperead.c  pipewrite.c
student@PRLAB-8:~/6015$ git --version
git version 2.43.0
student@PRLAB-8:~/6015$ git clone https://github.com/Sathiyasm3/nn.git
Cloning into 'nn'...
Username for 'https://github.com': 
Password for 'https://github.com': 








remote: Repository not found.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/nn.git/'

student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ 
student@PRLAB-8:~/6015$ git clone https://github.com/Sathiyasm3/nn.git
Cloning into 'nn'...
Username for 'https://github.com': Sathiyasm3
Password for 'https://Sathiyasm3@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/nn.git/'
student@PRLAB-8:~/6015$ git status
fatal: not a git repository (or any parent up to mount point /)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
student@PRLAB-8:~/6015$ git config --global user.name "Sathiyamurthy"
student@PRLAB-8:~/6015$ git config --global user.email "Sathiyasm3"
student@PRLAB-8:~/6015$ git config --global user.name "Sathiyasm3"
student@PRLAB-8:~/6015$ git config --global user.name "websm3@gmail.com"
student@PRLAB-8:~/6015$ ssh-keygen -t rsa -b 4096 -C "your.email@example.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/student/.ssh/id_rsa): eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsaEnter passphrase (empty for no passphrase): 
Enter same passphrase again: 

student@PRLAB-8:~/6015$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/student/6015/.git/
student@PRLAB-8:~/6015$  git clone https://github.com/Sathiyasm3/nn.git
Cloning into 'nn'...
Username for 'https://github.com': Sathiyasm3
Password for 'https://Sathiyasm3@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/nn.git/'
student@PRLAB-8:~/6015$ ssh-keygen -t rsa -b 4096 -C "your.email@example.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/student/.ssh/id_rsa): eval "$(ssh-agent -s)"
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in eval "$(ssh-agent -s)"
Your public key has been saved in eval "$(ssh-agent -s)".pub
The key fingerprint is:
SHA256:UoE/MHiPv7qt5s3XSnmLlUn+eyQtJv9ju3xx5RWhTuQ your.email@example.com
The key's randomart image is:
+---[RSA 4096]----+
|     . ..    . ..|
|    . =  .  o .. |
|     . *.    E  .|
|      ..+   o   o|
|      ..S.  .. oo|
|       ..  +.o+.=|
|         .o.*+ +o|
|      .+...+.oooo|
|     o=++.o.. +B*|
+----[SHA256]-----+
student@PRLAB-8:~/6015$ cat ~/.ssh/id_rsa.pub
cat: /home/student/.ssh/id_rsa.pub: No such file or directory
student@PRLAB-8:~/6015$ mkdir Mytest
student@PRLAB-8:~/6015$ cd Mytest
student@PRLAB-8:~/6015/Mytest$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/student/6015/Mytest/.git/
student@PRLAB-8:~/6015/Mytest$ echo "This is a git repo" > README.md
student@PRLAB-8:~/6015/Mytest$ git add README.md
student@PRLAB-8:~/6015/Mytest$ git commit -m "Initial commit"
[master (root-commit) 26b216e] Initial commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
student@PRLAB-8:~/6015/Mytest$ git remote add origin https://github.com/Sathiyasm3/Mytest.git
student@PRLAB-8:~/6015/Mytest$ git push -u origin master
Username for 'https://github.com': Sathiyasm3
Password for 'https://Sathiyasm3@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/Mytest.git/'
student@PRLAB-8:~/6015/Mytest$ ssh-keygen -t rsa -b 2048
Generating public/private rsa key pair.
Enter file in which to save the key (/home/student/.ssh/id_rsa): ^C
student@PRLAB-8:~/6015/Mytest$ git push -u origin master
Username for 'https://github.com': Sathiyasm3
Password for 'https://Sathiyasm3@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/Mytest.git/'
student@PRLAB-8:~/6015/Mytest$ git clone https://github.com/Sathiyasm3/nn.git
Cloning into 'nn'...
Username for 'https://github.com': 
Password for 'https://github.com': 
remote: Repository not found.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/nn.git/'
student@PRLAB-8:~/6015/Mytest$ git push -u origin master
Username for 'https://github.com': Sathiyasm3
Password for 'https://Sathiyasm3@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/Mytest.git/'
student@PRLAB-8:~/6015/Mytest$ git push -u origin master
Username for 'https://github.com': Sathiyasm3
Password for 'https://Sathiyasm3@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/Mytest.git/'
student@PRLAB-8:~/6015/Mytest$ git add README.md
student@PRLAB-8:~/6015/Mytest$ git push -u origin
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

student@PRLAB-8:~/6015/Mytest$ git pull
Username for 'https://github.com': 
Password for 'https://github.com': 
remote: Repository not found.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/Mytest.git/'
student@PRLAB-8:~/6015/Mytest$ 


tudent@PRLAB-8:~/6015/Mytest$ git commit -"hello"
usage: git commit [-a | --interactive | --patch] [-s] [-v] [-u<mode>] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>)]
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]
                  [--] [<pathspec>...]

    -q, --[no-]quiet      suppress summary after successful commit
    -v, --[no-]verbose    show diff in commit message template

Commit message options
    -F, --[no-]file <file>
                          read message from file
    --[no-]author <author>
                          override author for commit
    --[no-]date <date>    override date for commit
    -m, --[no-]message <message>
                          commit message
    -c, --[no-]reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --[no-]reuse-message <commit>
                          reuse message from specified commit
    --[no-]fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --[no-]squash <commit>
                          use autosquash formatted message to squash specified commit
    --[no-]reset-author   the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --[no-]signoff    add a Signed-off-by trailer
    -t, --[no-]template <file>
                          use specified template file
    -e, --[no-]edit       force edit of commit
    --[no-]cleanup <mode> how to strip spaces and #comments from message
    --[no-]status         include status in commit message template
    -S, --[no-]gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --[no-]all        commit all changed files
    -i, --[no-]include    add specified files to index for commit
    --[no-]interactive    interactively add files
    -p, --[no-]patch      interactively add changes
    -o, --[no-]only       commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --verify              opposite of --no-verify
    --[no-]dry-run        show what would be committed
    --[no-]short          show status concisely
    --[no-]branch         show branch information
    --[no-]ahead-behind   compute full ahead/behind values
    --[no-]porcelain      machine-readable output
    --[no-]long           show status in long format (default)
    -z, --[no-]null       terminate entries with NUL
    --[no-]amend          amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    --post-rewrite        opposite of --no-post-rewrite
    -u, --[no-]untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character

student@PRLAB-8:~/6015/Mytest$ git push -u origin
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

student@PRLAB-8:~/6015/Mytest$ git push --set-upstream origin master
Username for 'https://github.com': Sathiyasm3
Password for 'https://Sathiyasm3@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Sathiyasm3/Mytest.git/'
student@PRLAB-8:~/6015/Mytest$ git push --set-upstream origin master

