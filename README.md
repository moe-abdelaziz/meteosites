# meteosites
A demo project that uses Python and NASA data to find meteor landing sites

# Create SSH key
cat .ssh/id_rsa.pub

## Git
# use git clone with the SSH url from github to clone your project to your local machine
git clone git@github.com:moe-abdelaziz/meteosites.git

git remote -v

git status (will show the differences beetween your working dir and your repo)

- Add changes to your repo is a two step 

git add file_name file_name

git commit
git commit -m "add message for your log"
git push
git push origin master (origin is your local machine repo whereas master your github repo)
## Running
This project requires Python 3 and hte requests package.

'python3 find_meteors.py'