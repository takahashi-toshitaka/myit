`gem install chef`


error
```
RDoc::Parser::Ruby failure around line 52 of
lib/specinfra/command/windows/base/service.rb
```
env
```
[root@ip-10-1-0-21 ~]# ruby --version
ruby 2.0.0p648 (2015-12-16) [x86_64-linux]
[root@ip-10-1-0-21 ~]# gem --version
2.0.14.1
```
solution
```
gem install --no-rdoc  chef
```
ref  
https://github.com/pry/pry/issues/855
