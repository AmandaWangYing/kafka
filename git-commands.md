### Initialize git in local machine
    git init
    git add .
    git commit -m 'create kafka repo'
### Go to github.com and create kafka repository
    git remote add origin git@github.com:AmandaWangYing/kafka.git
    git remote -v
### Push changes to remote master
    git push --up-stream origin master
