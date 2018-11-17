this is a read me file

UM-L51FHTD7:second_day_stuff raviakkiraju$ git init
Reinitialized existing Git repository in /Users/raviakkiraju/Desktop/code/second_day_stuff/.git/

UM-L51FHTD7:second_day_stuff raviakkiraju$ git clone https://github.com/rakkiraju/myFirstRepo.git
Cloning into 'myFirstRepo'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.


UM-L51FHTD7:myFirstRepo raviakkiraju$ git add .

UM-L51FHTD7:myFirstRepo raviakkiraju$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   test.html

UM-L51FHTD7:myFirstRepo raviakkiraju$ git commit -m "My first commit on 11/17/2018 11:05 AM"
[master 3b0064d] My first commit on 11/17/2018 11:05 AM
 Committer: Ravi Akkiraju <raviakkiraju@UM-L51FHTD7.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 61 insertions(+)
 create mode 100644 test.html


UM-L51FHTD7:myFirstRepo raviakkiraju$ git push origin master
Username for 'https://github.com': rakkiraju
Password for 'https://rakkiraju@github.com':
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 927 bytes | 927.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/rakkiraju/myFirstRepo.git
   93e75d7..3b0064d  master -> master
UM-L51FHTD7:myFirstRepo raviakkiraju$
