#title
[socket]
https://shengyu7697.github.io/python-tcp-socket/
[service]
https://www.796t.com/article.php?id=196308
[git_ssh]
https://git-scm.com/book/en/v2/Git-on-the-Server-Generating-Your-SSH-Public-Key
ssh-keygen -o

~\.ssh

[git]
git config --global user.name "johnson"
git config --global user.email "yuanchenhu0309@gmail.com"
git config --list

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add -K ~/.ssh/id_rsa
git config --user.
git init
git clone ssh://git@bitbucket.itg.ti.com/scm/cac/cac.git
git add .
git commit -m "contents"
git push origin <branch name>
git remote add origin <url>
git remote -v

git tag version=0.0.0
git tag -a version=0.0.0 -m "<msg>"
git tag -d version=0.0.0
git tag -n

git push origin <tag_name>
git push origin --tags
git push origin --delete <tag_name> 

git branch -r
git branch -a
git branch <created new branch>

git checkout -b dev
git checkout master 
git merge dev
git checkout dev
git merge master 

[git_commit]
    [Fix bug]
    [Add doc]
    [Dev]
    [New feature]
    [Maintain]
    

[pip]
    python -m pip install  --proxy=http://webproxy.ext.ti.com:80
[env]

    pipreqs C:\Users\a0491094\Desktop\automation\CAC\SRC
    virtualenv <name>
[env_activate]
in cmd only
cd C:\Users\a0491094\Desktop\automation\CAC\MISC\CAC_Env\Scripts
activate
    pip install -r <request>
deactivate
cd C:\Users\a0491094\Desktop\automation\CAC\src
pyinstaller -F CAC.py
pyinstaller -F --noconsole CAC.py
move C:\Users\a0491094\Desktop\automation\CAC\SRC\dist\fuck.txt C:\Users\a0491094\Desktop\automation\CAC\SRC

[pyinstaller]
pyinstaller -F -w <file> 
        .exe need to move out from dist to cac.py location


material
http://c.biancheng.net/view/2690.html

[reverse_exe]
https://www.cnblogs.com/pcat/p/11625300.html
[cmd]
net use
explorer shell: startup