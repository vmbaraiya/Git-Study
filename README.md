# Git-Study


## What is version control
_Version control systems are a category of software tools that help a software team manage changes to source code over time. Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members._

## Source code management
_Source code management (SCM) is used to track modifications to a source code repository. SCM tracks a running history of changes to a code base and helps resolve conflicts when merging updates from multiple contributors. SCM is also synonymous with Version control. 
As software projects grow in lines of code and contributor head count, the costs of communication overhead and management complexity also grow. SCM is a critical tool to alleviate the organizational strain of growing development costs._

## What is Git

_Git is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel. A staggering number of software projects rely on Git for version control, including commercial projects as well as open source. Developers who have worked with Git are well represented in the pool of available software development talent and it works well on a wide range of operating systems and IDEs (Integrated Development Environments).
Having a distributed architecture, Git is an example of a DVCS (hence Distributed Version Control System). Rather than have only one single place for the full version history of the software as is common in once-popular version control systems like CVS or Subversion (also known as SVN), in Git, every developer's working copy of the code is also a repository that can contain the full history of all changes._

### GETTING STARTED

1. Install Git

```shell
yum install git
```

2. Check the git version
```shell
git --version
```
3. Configure Git with user information

```shell
git config --global user.name "<username>"
```

```shell
git config --global user.email "<useremailaddress>"
```
Check if the .gitconfig file is available at home location of the user for which git is installed
```shell
cat ~/.gitconfig
```
If you don't have .gitocnfig file that means your git config is not set up

4. What is Repository

_Repository is a place where all code is hosted remotely._
> A Git repository is a virtual storage of your project. It allows you to save versions of your code, which you can access when needed.

> Create a new Repsitory using a [New Repository option](https://github.com/new) 

> git clone: git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository on your local system.
> When you connect to a GitHub repository from Git, you'll need to authenticate with GitHub using either HTTPS or SSH.
<dl>
<dt>There are way to get repo on your local system using git clone</dt>
<dd>1. https</dd>
<dd>2. ssh </dd>

<dt>https</dt>
<dd>The https:// clone URLs are available on all repositories, public and private. These URLs work everywhere--even if you are behind a firewall or proxy.</dd>
<dd> An HTTPS connection allows credential.helper to cache your password.</dd>

<dt>ssh</dt>
<dd>In case of SSH Keys are used for authentication.If you clone with SSH, you must generate SSH keys on each computer you use to push or pull from GitHub.</dd>
</dl>

> Please check for more details regarding SSH [Connecting to GitHub with SSH](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh)

