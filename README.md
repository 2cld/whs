[edit - github](https://github.com/2cld/whs/edit/master/README.md)

# Winfield Historical Society [Test Web Site](./web)

- [current host gate](https://sitecontrol-sp.gate.com)
- has ssh 
- See notes from Carol
- Talked to Carol on 2024.01.31 Wed and got hosting info
- [http://www.winfieldhistoricalsociety.com/](http://www.winfieldhistoricalsociety.com/)
- [https://www.henrycountyheritagetrust.org/](https://www.henrycountyheritagetrust.org/) - example of format
- added winfieldhistoricalsociety@gmail.com email address - whs-chris winfield-historical-society What#Time#
- Updated Domain Name Contacts

```
ghadmin@Cybertruck:~$ git push -u origin master
ghadmin@Cybertruck:~$ git remote -v
```

```
ghadmin@Cybertruck:~$ history
    1  git status
    2  cd /mnt/c/Users/ghadmin/
    3  ls
    4  ls -alu
    5  ls
    6  cd BlenderProjects/
    7  ls
    8  git clone https://github.com/grasshorse/blenderRepo.git .
    9  git clone https://github.com/grasshorse/blenderRepo.git
   10  ssh cat@winfieldhistoricalsociety.com
   11  ssh christrees@winfieldhistoricalsociety.com
   12  scp christrees@winfieldhistoricalsociety.com:cat-backup-web20240202.tar.gz .
   13  pwd
   14  mv cat-backup-web20240202.tar.gz /mnt/d/
   15  ls
   16  cd /mnt/d/
   17  ls -alu
   18  tar -xvf cat-backup-web20240202.tar.gz .
   19  cd ~
   20  mv /mnt/d/cat-backup-web20240202.tar.gz .
   21  ls
   22  tar -xvf cat-backup-web20240202.tar.gz .
   23  tar -xvf cat-backup-web20240202.tar.gz
   24  ls
   25  ls -alu
   26  ssh christrees@winfieldhistoricalsociety.com
   27  scp christrees@winfieldhistoricalsociety.com:cat-backup-whs-web-20240202.tar.gz
   28  ls
   29  rm -rf web
   30  ls
   31  mkdir whs-web
   32  ls -alu
   33  rm cat-backup-web20240202.tar.gz
   34  tar -xvf cat-backup-whs-web-20240202.tar.gz -C whs-web/
   35  ls
   36  cd whs-web/
   37  ls
   38  cd web/
   39  ls
   40  cd ..
   41  ls
   42  vi README.md
   43  git status
   44  cd ..
   45  pwd
   46  cd whs-web/
   47  ls
   48  git init
   49  git commit 'old website'
   50  git commit -m 'old website'
   51  git config --global user.email "ghadmin@horseoff.com"
   52  git config --global user.name "ghadmin"
   53  git remote add origin https://github.com/2cld/whs.git
   54  git branch -M main
   55  git status
   56  git add *
   57  git status
   58  git commit -m 'old website'
   59  git status
   60  git branch
   61  git remote add origin https://github.com/2cld/whs.git
   62  git push -u origin master
   63  cd ~
   64  ls -alu
   65  ls .ssh
   66  ssh-keygen
   67  cat .ssh/id_rsa.pub
   68  git push -u origin master
   69  git remote show
   70  git show remote
   71  git remote -v
   72  ls
   73  cd whs-web/
   74  git push -u origin master
   75  ssh -T git@github.com
   76  git remote -v
   77  git push -u origin master
   78  cd ..
   79  cd .ssh
   80  ls
   81  vi config
   82  cd ..
   83  cd whs-web/
   84  git status
   85  git push -u origin master
   86  git push
   87  git push --set-upstream origin master
   88  ssh -T @github.com
   89  vi ../.ssh/config
   90  git -c core.sshCommand="ssh -v" push -u origin master
   91  git remove -v
   92  git remote -v
   93  vi .git/config
   94  git status
   95  git push -u origin master
   96  vi ../.ssh/config
   97  vi .git/config
   98  git config user.name
   99  git config user.email
  100  git config user.name "grasshorse"
  101  git config user.name
  102  git push -u origin master
  103  vi .git/config
  104  git push -u origin master
  105  git -v
  106  git remote -v
  107  git remote set-url origin git@github.com:2cld/whs.git
  108  git remote -v
  109  git push -u origin master
  110  history
```

```
ghadmin@Cybertruck:~$ cat .ssh/config
Host github.com
 Hostname ssh.github.com
 Port 443
ghadmin@Cybertruck:~$
```

```
ghadmin@Cybertruck:~$ cat whs-web/.git/config
[core]
        repositoryformatversion = 0
        filemode = true
        bare = false
        logallrefupdates = true
[remote "origin"]
        url = git@github.com:2cld/whs.git
        fetch = +refs/heads/*:refs/remotes/origin/*
[user]
        name = grasshorse
[branch "master"]
        remote = origin
        merge = refs/heads/master
ghadmin@Cybertruck:~$
```

[school of trade to move](https://www.youtube.com/@SchoolOfTrade)
