PS D:\The GYM git Exercises\BUNDLE 4> git init
error: pathspec 'main' did not match any file(s) known to git
PS D:\The GYM git Exercises\BUNDLE 4> git add README.md
PS D:\The GYM git Exercises\BUNDLE 4> git commit -m "Initial commit"
 create mode 100644 README.md
PS D:\The GYM git Exercises\BUNDLE 4> git branch -M main
PS D:\The GYM git Exercises\BUNDLE 4> git branch
* main
PS D:\The GYM git Exercises\BUNDLE 4> git remote add git-copy https://github.com/bdushime/Bundle4_Exercise1.git
PS D:\The GYM git Exercises\BUNDLE 4> git remote -v
git-copy        https://github.com/bdushime/Bundle4_Exercise1.git (push)
PS D:\The GYM git Exercises\BUNDLE 4> origin <https://github.com/bdushime/Bundle4_Exercise1.git> (fetch)
At line:1 char:8
+ origin <https://github.com/bdushime/Bundle4_Exercise1.git> (fetch)
+        ~
The '<' operator is reserved for future use.
    + FullyQualifiedErrorId : RedirectionNotSupported
 
PS D:\The GYM git Exercises\BUNDLE 4> origin    <URL of the first remote> (fetch)
At line:1 char:11
+ origin    <URL of the first remote> (fetch)
+           ~
The '<' operator is reserved for future use.
    + FullyQualifiedErrorId : RedirectionNotSupported
 
PS D:\The GYM git Exercises\BUNDLE 4> origin    <URL of the first remote> (push)
At line:1 char:11
+ origin    <URL of the first remote> (push)
+           ~
The '<' operator is reserved for future use.
    + FullyQualifiedErrorId : RedirectionNotSupported
 
PS D:\The GYM git Exercises\BUNDLE 4> git-copy  <URL of the new remote> (fetch)
At line:1 char:11
+ git-copy  <URL of the new remote> (fetch)
+           ~
The '<' operator is reserved for future use.
 
PS D:\The GYM git Exercises\BUNDLE 4> git-copy  <URL of the new remote> (push)
At line:1 char:11
+ git-copy  <URL of the new remote> (push)
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
PS D:\The GYM git Exercises\BUNDLE 4> git add .
PS D:\The GYM git Exercises\BUNDLE 4> git commit -m 'Update index'
[main 3f2532c] Update index
 1 file changed, 11 insertions(+)
 create mode 100644 index.html
PS D:\The GYM git Exercises\BUNDLE 4> git remote add git-copy https://github.com/bdushime/Bundle4-Exercise1.5.git
error: remote git-copy already exists.
e1.5.git
PS D:\The GYM git Exercises\BUNDLE 4> git remote -v
git-copy        https://github.com/bdushime/Bundle4_Exercise1.git (fetch)
git-copy        https://github.com/bdushime/Bundle4_Exercise1.git (push)
origin  https://github.com/bdushime/Bundle4-Exercise1.5.git (fetch)
origin  https://github.com/bdushime/Bundle4-Exercise1.5.git (push)
PS D:\The GYM git Exercises\BUNDLE 4> git add .
PS D:\The GYM git Exercises\BUNDLE 4> git commit -m 'Update index'
nothing to commit, working tree clean
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 655 bytes | 163.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/bdushime/Bundle4-Exercise1.5.git
 * [new branch]      main -> main
PS D:\The GYM git Exercises\BUNDLE 4> git push-copy main
git: 'push-copy' is not a git command. See 'git --help'.
PS D:\The GYM git Exercises\BUNDLE 4> git push git-copy main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 655 bytes | 218.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/bdushime/Bundle4_Exercise1.git
 * [new branch]      main -> main
PS D:\The GYM git Exercises\BUNDLE 4> 
