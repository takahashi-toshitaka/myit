#repoquery

##install
```bash
yum -y install yum-utils
```


##example
```
 repoquery -l yum-utils
 
/etc/bash_completion.d
/etc/bash_completion.d/yum-utils.bash
/usr/bin/debuginfo-install
/usr/bin/find-repos-of-install
/usr/bin/needs-restarting
/usr/bin/package-cleanup
/usr/bin/repo-graph
/usr/bin/repo-rss
...
```

```bash
rpm -ql
```

like as this command.  
"rpm" command can only use for the local package that are installed or downloaded.  
"repoquery" can give information from yum repositories without install package.

##options

- -i show general information about package similarly to "rpm -qi"
- -l list files in package.
- -s show package source rpm name.
