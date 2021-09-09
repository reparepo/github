```
$ git config credential.helper store
$ git push https://github.com/owner/repo.git

Username for 'https://github.com': <USERNAME>
Password for 'https://USERNAME@github.com': <PASSWORD>

Also specify caching expire,

$ git config --global credential.helper 'cache --timeout 7200'
```
