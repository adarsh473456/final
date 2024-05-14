"welcome to rgmp sir"

mkdir demo
cd demo
echo "welcome to rgmp sir">>README.md
type README.md
git init
git add README.md
git commit -m "first commit"
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'adars@ADARSH-TECH.(none)')

C:\demo>git config --global user.email "adarshtech47345@gmail.com"

C:\demo>git config --global user.name "adarsh473456"

C:\demo>git commit -m "first commit"
[master (root-commit) 639492a] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md


C:\demo>git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

C:\demo>git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

C:\demo>
