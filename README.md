# syne_devops

git clone https://github.com/reddychaitu2002/syne_devops.git

cd syne_devops/

git add index.html

git commit -m "Added Index.html"

ec2-user:~/environment/syne_devops (master) $ history
    1  sudo yum install git
    2  git add https://github.com/reddychaitu2002/syne_devops.git
    3  git clone https://github.com/reddychaitu2002/syne_devops.git
    4  cd syne_devops/
    5  git add index.html
    6  git status
    7  git commit -m "Added Index.html"
    8  git push 
    9  history
   10  git branch -v
   11  git branch idea1
   12  git branch idea2
   13  git branch -v
   14  get checkout idea1
   15  git checkout idea1
   16  history
   17  git add *
   18  git commit -m "idea1 code"
   19  git checkout master
   20  git merge idea1
   21  history
   22  git add *
   23  git commit -m "changes in Master"
   24  git checkout idea1
   25  git add *
   26  git commit -m "changes in idea1"
   27  git checkout master
   28  git merge idea1
   29  git add *
   30  git commit -m "merged"
   31  git remote -v
   32  history
   33  cls
   34  git branch -v --all
   35  git push --set-upstream master: dev1.0  --wrong
   36  git push --set-upstream master: dev-1.0  --wrong
   37  git push --set-upstream origin master: dev-1.0  --wrong
   38  git push --set-upstream origin master:dev-1.0 --correct
   39  git commit -m "local change"
   40  git push --set-upstream origin master:dev-1.0
   41  git pull origin dev-1.0
   42  git commit -m "local change"
   43  git add *
   44  git commit -m "local change"
   45  git pull origin dev-1.0
   46  git push --set-upstream origin master:dev-1.0
   47  git add *
   48  git commit -m "local change"
   49  git push --set-upstream origin master:dev-1.0
   50  history
   
   
   
   
   ****************Jenkins****************
   
   1) List all the tools   (git, ssh, shell script)
   2) Install the tool on Jenkins server
   3) Configure the tool
   4) Make sure tool can be invoked by Jenkins user
   5) Install the plugins   (git, ssh)
   6) Restart jenkins
   7) Configure the plugins
   8) use the plugin in the pipeline