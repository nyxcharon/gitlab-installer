gitlab-installer
================

Debian/Ubuntu package for gitlab.    
Configures Apache to proxypass to gitlab by default.    
Apache is configured to use SSL, so have your certs ready.    
Package also assumes that there is outbound access so that gitlab itself can be downloaded   


```
$ wget https://github.com/nyxcharon/gitlab-installer/raw/master/dist/ubuntu/gitlab-installer_13.1.0_all.deb 
$ sudo dpkg -i gitlab-installer_13.1.0_all.deb
$ sudo gitlab-installer-setup
```



