## Git

Que es eso?

--

Distributed revsion control and source code management system that focuses on speed. It was originally developed by Linus Torvalds to help with Linux Kernel Development.

--

Differences with SVN

* Less clutter.  Git stores only one .git folder with all the revision information at the top of the repository.  SVN likes to keep that information at every level of the directory tree;

* Decentralized

* [More](http://stackoverflow.com/questions/871/why-is-git-better-than-subversion)

--

Differences from CVS

* Decentralized
* [More](http://stackoverflow.com/questions/802573/difference-between-git-and-cvs)

---

## Install Git

* OSX -> http://code.google.com/p/git-osx-installer/downloads/list?can=3
* WINDOWS -> http://code.google.com/p/msysgit/downloads/list?can=3
* Linux -> http://book.git-scm.com/2_installing_git.html

---

## How Git Works
* Git thinks of your code in terms of snapshots, not differences;
* Almost every operation is local
* Git operations only add data to the database;  Actions are mostly never undoable.
*

--

## Local Operations

![local ops](http://git-scm.com/figures/18333fig0106-tn.png)


--

## GitHub
* Github is a repository hosting service for git
* Adds three features -- and makes them easier to use
  * Fork
  * Pull Request
  * Merge
* Provides hosting of static pages
* [SOOO Much More](https://github.com/blog/category/ship)

--

## Github's Git Workflow

* Fork
* Clone
* Code
* Pull Request
* Merge

--

## Static Page Hosting
* GitHub allows for hosting of Static Pages
* Allows you to run websites on the fastest servers in the world.

# For Free {% fragment %}

---

## Let's Play
* AKA I dont wanna talk anymore {% fragment %}

--

## Something Simple

Create a home page for yourself on GitHub
* username.github.io repo {% fragment %}
* index.html {% fragment %}

---

## But you don't wanna hand write HTML do ya?
* You want to use markdown {% fragment %}
* Jekyll lets you write markdown and will autogenerate HTML {% fragment %}
* Push and Build {% fragment %}
* Github Standard {% fragment %}

---

## Get Ready for some Jekyll Love
* `gem install jekyll` {% fragment %}
* `git clone git@github.com:CoquiCoders/puerto-rico-ideas.git` {% fragment %}
* `jekyll serve --watch` {% fragment %}
* `http://localhost:4000` {% fragment %}

--

Puerto Rico Ideas
What's an idea you've had to make things better in PR;
{% fragment %}

