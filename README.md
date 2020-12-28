## Git installation —

### GYAN —

Git is a distributed version-control system for tracking changes in any set of files, originally designed for coordinating work among programmers cooperating on source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

### YUM installation —

[root@192 anup]#  yum update

[root@192 anup]#  yum install git 

[root@192 anup]#  git --version 


### Install Git from Source — 

[root@192 anup]# yum groupinstall "Development Tools"

[root@192 anup]# yum install gettext-devel openssl-devel perl-CPAN perl-devel zlib-devel


[root@192 anup]# wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.9.5.tar.gz

[root@192 anup]# tar -xvzf git-2.9.5.tar.gz

[root@192 anup]# cd git-2.9.5/

[root@192 git-2.9.5]# make configure

[root@192 git-2.9.5]# ./configure --prefix=/usr/local

[root@192 git-2.9.5]# make install

[root@192 git-2.9.5]# git --version

```git version 2.9.5```


.
  
**@ By — Anup Kumar Mondal**

