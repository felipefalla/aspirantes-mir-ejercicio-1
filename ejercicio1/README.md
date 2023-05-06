1. PS C:\users\master

2.PS C:\users\master\desktop> mkdir ejercicios


    Directorio: C:\users\master\desktop


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        5/05/2023  7:13 p.m.                ejercicios

3.PS C:\users\master\desktop> cd ejercicios/
PS C:\users\master\desktop\ejercicios>

5.PS C:\users\master\desktop\ejercicios> ls


    Directorio: C:\users\master\desktop\ejercicios


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        5/05/2023  7:15 p.m.                ejercicio1

6.PS C:\users\master\desktop\ejercicios\ejercicio1> ni README.md


    Directorio: C:\users\master\desktop\ejercicios\ejercicio1


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        5/05/2023  7:19 p.m.              0 README.md

7.PS C:\users\master\desktop\ejercicios\ejercicio1> git config -l
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=felipe
user.email=pipefallaguz97@gmail.com

8.PS C:\users\master\desktop\ejercicios> git init
Initialized empty Git repository in C:/Users/MASTER/Desktop/ejercicios/.git/

9.PS C:\users\master\desktop\ejercicios> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add
PS C:\users\master\desktop\ejercicios> git add .
PS C:\users\master\desktop\ejercicios> git commit -m'version inicial'
[master (root-commit) b6ab195] version inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md
PS C:\users\master\desktop\ejercicios>