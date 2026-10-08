ericalinux@LAPTOP-4ADQLHUL:~$ pwd
/home/ericalinux
ericalinux@LAPTOP-4ADQLHUL:~$ whoami
ericalinux
ericalinux@LAPTOP-4ADQLHUL:~$ ls -lah
total 40K
drwxr-x--- 5 ericalinux ericalinux 4.0K Oct  8 13:00 .
drwxr-xr-x 3 root       root       4.0K Oct  8 09:25 ..
-rw------- 1 ericalinux ericalinux 3.0K Oct  8 13:00 .bash_history
-rw-r--r-- 1 ericalinux ericalinux  220 Oct  8 09:25 .bash_logout
-rw-r--r-- 1 ericalinux ericalinux 3.7K Oct  8 09:25 .bashrc
drwxr-x--- 4 ericalinux ericalinux 4.0K Oct  8 09:35 .cache
drwxr-x--- 3 ericalinux ericalinux 4.0K Oct  8 09:35 .config
drwxr-xr-x 2 ericalinux ericalinux 4.0K Oct  8 09:35 .landscape
-rw------- 1 ericalinux ericalinux   48 Oct  8 12:51 .lesshst
-rw-r--r-- 1 ericalinux ericalinux    0 Oct  8 09:35 .motd_shown
-rw-r--r-- 1 ericalinux ericalinux  807 Oct  8 09:25 .profile
ericalinux@LAPTOP-4ADQLHUL:~$ cd /etc
ericalinux@LAPTOP-4ADQLHUL:/etc$ pwd
/etc
ericalinux@LAPTOP-4ADQLHUL:/etc$ cd /var/log
ericalinux@LAPTOP-4ADQLHUL:/var/log$ ls -lah
total 1.1M
drwxrwxr-x   9 root      syslog          4.0K Oct  8 12:37 .
drwxr-xr-x  13 root      root            4.0K Oct  8 09:08 ..
lrwxrwxrwx   1 root      root              39 Aug 27 13:11 README -> ../../usr/share/doc/systemd/README.logs
-rw-r--r--   1 root      root             21K Aug 27 13:13 alternatives.log
drwxr-xr-x   2 root      root            4.0K Oct  8 11:40 apt
-rw-r-----   1 syslog    adm              16K Oct  8 12:37 auth.log
-rw-r--r--   1 root      root            145K Aug 27 13:11 bootstrap.log
-rw-rw----   1 root      utmp               0 Aug 27 13:10 btmp
drwxr-x---   2 _chrony   _chrony         4.0K Oct  8 09:08 chrony
drwxr-xr-x   2 root      root            4.0K Aug 24 13:06 dist-upgrade
-rw-r-----   1 root      adm              68K Oct  8 12:37 dmesg
-rw-r-----   1 root      adm              33K Oct  8 11:37 dmesg.0
-rw-r-----   1 root      adm              20K Oct  8 09:09 dmesg.1.gz
-rw-r-----   1 root      adm              11K Oct  8 09:08 dmesg.2.gz
-rw-r--r--   1 root      root            314K Oct  8 11:40 dpkg.log
-rw-r--r--   1 root      root             790 Aug 27 13:13 fontconfig.log
drwxr-sr-x+  3 root      systemd-journal 4.0K Oct  8 09:08 journal
-rw-r-----   1 syslog    adm              99K Oct  8 12:39 kern.log
drwxr-xr-x   2 landscape landscape       4.0K Oct  8 09:08 landscape
-rw-rw-r--   1 root      utmp               0 Aug 27 13:10 lastlog
drwx------   2 root      root            4.0K Aug 27 13:11 private
-rw-r-----   1 syslog    adm             310K Oct  8 12:52 syslog
drwxr-x---   2 root      adm             4.0K Oct  8 09:08 unattended-upgrades
-rw-rw-r--   1 root      utmp            1.5K Oct  8 12:37 wtmp
ericalinux@LAPTOP-4ADQLHUL:/var/log$ cd ~
ericalinux@LAPTOP-4ADQLHUL:~$ pwd
/home/ericalinux
ericalinux@LAPTOP-4ADQLHUL:~$ cd /var
ericalinux@LAPTOP-4ADQLHUL:/var$ cd log
ericalinux@LAPTOP-4ADQLHUL:/var/log$ pwd
/var/log
ericalinux@LAPTOP-4ADQLHUL:/var/log$ cd ..
ericalinux@LAPTOP-4ADQLHUL:/var$ pwd
/var
ericalinux@LAPTOP-4ADQLHUL:/var$ cd -
/var/log
ericalinux@LAPTOP-4ADQLHUL:/var/log$ cd
ericalinux@LAPTOP-4ADQLHUL:~$ pwd
/home/ericalinux
ericalinux@LAPTOP-4ADQLHUL:~$ tree --version
tree v2.3.1 © 1996 - 2026 by Steve Baker, Thomas Moore, Francesc Rocher, Florian Sesser, Kyosuke Tokoro
ericalinux@LAPTOP-4ADQLHUL:~$ mkdir -p ~/empresa/{rh,ti,financas/backup,rascunhos}
ericalinux@LAPTOP-4ADQLHUL:~$ cd ~/empresa
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ pwd
/home/ericalinux/empresa
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ tree
.
├── financas
│   └── backup
├── rascunhos
├── rh
└── ti

6 directories, 0 files
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ touch rh/relatorio_jan.txt rh/relatorio_fev.txt rh/contrato_alice.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ touch ti/config.log ti/deploy.sh ti/erros.log
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ touch ti/relatorio_mar.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ touch financas/orcamento_2026.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ touch rascunhos/nota_antiga.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ tree
.
├── financas
│   ├── backup
│   └── orcamento_2026.txt
├── rascunhos
│   └── nota_antiga.txt
├── rh
│   ├── contrato_alice.txt
│   ├── relatorio_fev.txt
│   └── relatorio_jan.txt
└── ti
    ├── config.log
    ├── deploy.sh
    ├── erros.log
    └── relatorio_mar.txt

6 directories, 9 files
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ ls -lh rh/
total 0
-rw-r--r-- 1 ericalinux ericalinux 0 Oct  8 13:16 contrato_alice.txt
-rw-r--r-- 1 ericalinux ericalinux 0 Oct  8 13:16 relatorio_fev.txt
-rw-r--r-- 1 ericalinux ericalinux 0 Oct  8 13:16 relatorio_jan.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ stat rh/relatorio_jan.txt
  File: rh/relatorio_jan.txt
  size: 0               Blocks: 0          IO Block: 4096   regular empty file
Device: 8,48    Inode: 41938       Links: 1
Access: (0644/-rw-r--r--)  Uid: ( 1000/ericalinux)   Gid: ( 1000/ericalinux)
Access: 2026-10-08 13:16:27.970369959 -0100
Modify: 2026-10-08 13:16:27.970369959 -0100
Change: 2026-10-08 13:16:27.970369959 -0100
 Birth: 2026-10-08 13:16:27.970369959 -0100
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ mv -i ti/relatorio_mar.txt rh/
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ mkdir -p rh/arquivo_2026
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ mv rh/relatorio_jan.txt rh/arquivo_2026/
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ mv rh/contrato_alice.txt rh/contrato_alice_v1.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ ls rh/ ti/
rh/:
arquivo_2026  contrato_alice_v1.txt  relatorio_fev.txt  relatorio_mar.txt

ti/:
config.log  deploy.sh  erros.log
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ touch rh/rascunho.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ mv -i rh/rascunho.txt rh/relatorio_fev.txt
mv: overwrite 'rh/relatorio_fev.txt'? n
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ cp financas/orcamento_2026.txt financas/backup/orcamento_2026.bak
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ cp -rp financas/ ~/backup_financas/
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ tree ~/backup_financas
/home/ericalinux/backup_financas
├── backup
│   └── orcamento_2026.bak
└── orcamento_2026.txt

2 directories, 2 files
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ rm -i rh/rascunho.txt
rm: remove regular empty file 'rh/rascunho.txt'? y
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ ls rascunhos/
nota_antiga.txt
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ rm -ri rascunhos/
rm: descend into directory 'rascunhos/'? y
rm: remove regular empty file 'rascunhos/nota_antiga.txt'? y
rm: remove directory 'rascunhos/'? y
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ tree
.
├── financas
│   ├── backup
│   │   └── orcamento_2026.bak
│   └── orcamento_2026.txt
├── rh
│   ├── arquivo_2026
│   │   └── relatorio_jan.txt
│   ├── contrato_alice_v1.txt
│   ├── relatorio_fev.txt
│   └── relatorio_mar.txt
└── ti
    ├── config.log
    ├── deploy.sh
    └── erros.log

6 directories, 9 files
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ cd ~/empresa && nano README.md
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ cat README.md
# CVTECH Lda. — Estrutura Documental
Responsável: <Erica>
Data: <08/10/2016>
## Departamentos
- rh/ — relatórios e contratos (arquivo em rh/arquivo_2026/)
- ti/ — configurações, scripts e logs de TI
- financas/ — orçamento e cópias em financas/backup/
## Operações realizadas
- relatorio_mar.txt movido de ti/ para rh/
- relatorio_jan.txt arquivado em rh/arquivo_2026/
- contrato_alice.txt renomeado para contrato_alice_v1.txt
- cópia de segurança de financas/ em ~/backup_financas/
- pasta rascunhos/ removida
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ less README.md
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ less /etc/services
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ cp README.md README.md.bak
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ nano README.md
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ cat README.md.bak
# CVTECH Lda. — Estrutura Documental
Responsável: <Erica>
Data: <08/10/2026>
## Departamentos
- rh/ — relatórios e contratos (arquivo em rh/arquivo_2026/)
- ti/ — configurações, scripts e logs de TI
- financas/ — orçamento e cópias em financas/backup/
## Operações realizadas
- relatorio_mar.txt movido de ti/ para rh/
- relatorio_jan.txt arquivado em rh/arquivo_2026/
- contrato_alice.txt renomeado para contrato_alice_v1.txt
- cópia de segurança de financas/ em ~/backup_financas/
- pasta rascunhos/ removida
ericalinux@LAPTOP-4ADQLHUL:~/empresa$ rm -i README.md.bak
rm: remove regular file 'README.md.bak'? y
ericalinux@LAPTOP-4ADQLHUL:~/empresa$
