# GitTools 

[![Join the chat at https://gitter.im/yaras/GitTools](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/yaras/GitTools?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Tools for git. 

Requirements:

* python
* git

## git-intersection

Finds intersection of files between commits or commit ranges

**Usage**

Create alias:

```
git config --global alias.intersection '!python /path/to/git-intersection.py'
```

**Examples:**

Find intersection between last two commits:

```
git intersection master master~1
```

Find intersection between two commit ranges

```
git intersection e9b5c58..master e9b5c58..feat-1234
```
