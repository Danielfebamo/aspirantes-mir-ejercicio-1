PS C:\Users\DanielB\desktop> pwd

Path
----
C:\Users\DanielB\desktop


PS C:\Users\DanielB\desktop> mkdir Ejercicios


    Directorio: C:\Users\DanielB\desktop


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         5/10/2023   6:45 PM                Ejercicios


PS C:\Users\DanielB\desktop> cd ejercicios
PS C:\Users\DanielB\desktop\ejercicios> git config -l
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
user.name=Daniel
user.email=bilin241@hotmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
PS C:\Users\DanielB\desktop\ejercicios> git init
Initialized empty Git repository in C:/Users/DanielB/Desktop/Ejercicios/.git/
PS C:\Users\DanielB\desktop\ejercicios> git add .
PS C:\Users\DanielB\desktop\ejercicios> git commit -m "version inicial"
[master (root-commit) 62ec952] version inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Ejercicio1/README.md
PS C:\Users\DanielB\desktop\ejercicios>