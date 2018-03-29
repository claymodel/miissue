# miissue
Git Issue Migration Tool (Supports for Github and Gitbucket)

# migrating git issues between repositories of github and gitbucket

 - Provide the source and destination git url.
 - Provide the source and destination git token.
 - Provide the repository name.
 - Provide the desired issues closed or open issues. by default it grabs the closed issues.


# Command line examples:

### Migrating the open issues
```
miissue -p "surl http://source-host/api/v3" -p "durl http://dest-host/api/v3" -p "stoken xxxx" -p "dtoken xxxx" -p "srepo name1/repo1" -p "drepo name2/repo1" -p "stat open"
```

### Migrating the closed issues
```
miissue -p "surl http://source-host/api/v3" -p "durl http://dest-host/api/v3" -p "stoken xxxx" -p "dtoken xxxx" -p "srepo name1/repo1" -p "drepo name2/repo1"
```

# Installation

https://pypi.python.org/pypi/miissue/0.0.1

Git Issue migration tool (Works for Github, Gitbucket)

pre-requirement
	python 2.7.x

installation
	pip install miissue


surl = source git url
durl = destination git url

srepo = source repository 
drepo = destination repository

stat = open for open issue migration
stat = closed for closed issue migration

