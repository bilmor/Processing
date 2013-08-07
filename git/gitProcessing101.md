# Git Processing 101
### distributed version control for sketches

* open.
* fast.
* scalable.

## Save and Share

* Every directory is repository.
	* history and version tracking
* Not dependent on network access or central server.
	* connectivity != blocker
* Free software.
	* GNU General Public License version 2

## Back in the day
* FTP
* Copies

Do not make copies of sketches.<br>
Make commits @ logical stopping points!

## Collaboration
same files == version nightmare

* Different times
* Some overlaps

## Revision History
### Content Changes

* Who
* What
* When
* Why

## Features
* local branching
* staging areas
* multiple workflows

*Example:* [John Resig's port of the Processing to JavaScript.](https://github.com/jeresig/processing-js)

* Code
* Network
* Graphs

## <code>$ git log</code>
* copyright holder of BitKeeper withdrew free use of product
* Linus Torvalds (core developer Linux) builds something better

## Priority
* Performance

<blockquote>
  <p>His goal was for patches to take three seconds.</p>
  <small><cite title="Wikipedia">Wikipedia</cite></small>
</blockquote>

## Design Criteria
* Opposite of Concurrent Versions System (CVS)
* Distributed workflow
* Safeguard against corruption

## Open Source

<blockquote>
  <p>open source as a philosophy promotes a universal access via free license to a product's design or blueprint<br>
  	and universal redistribution of that design or blueprint, including subsequent improvements to it by anyone.</p>
  <small><cite title="Wikipedia">Wikipedia</cite></small>
</blockquote>

* Apache
* Linux
* Ruby
* WordPress
* Processing
* Arduino
* SuperCollider

### [OpenProcessing](http://openprocessing.org/)
### [Open Source Initiative](http://opensource.org/osd) (OSI)

## GitHub
* GUI
* Social Coding

### Sign up for [GitHub](https://github.com)

## Installer
* [Downloads](http://git-scm.com/downloads)

## Exercise

* create processing repository on GitHub
* copy HTTPS clone URL
* Open Terminal

### Clone repo.
git clone (HTTPS clone URL)<br>
$ ```git clone https://github.com/earth2travis/processing.git```

### See current state of project.
$ ```git status```

### To start tracking changes made to octocat.txt, add it to the staging area.
$ ```git add octocat.txt```

### Move changes to repository running commit command and describing changes.
$ ```git commit -m "Add cute octocat story"```

### Use wildcards for adding many files of same type.
$ ```git add '*.txt'```

### Browse updates with journal of what has changed.
$ ```git log```

### Push local files to server by adding remote repository.
* Remote name: origin
* Repository URL: https://github.com/try-git/try_git.git

$ ```git remote add origin https://github.com/try-git/try_git.git```

### Push tells Git where to put our commits.
* Remote (repo): origin
* Local (branch): master
* -u: Remember parameters, for origin and master.

$ ```git push -u origin master```

### Check for changes on repository and pull down updates. 
$ ```git pull origin master```

### View changes since last commit.
* Pointers hold positions within different commits.
* By default HEAD points to your most recent commit.
$ ```git diff HEAD```

### Look at changes in files already staged.
$ ```git diff --staged```

### Unstage files.
$ ```git reset octofamily/octodog.txt```

### Undo changes back to last commit.
git checkout -- (target)

$ ```git checkout -- octocat.txt```

### Create branch to add feature or fix bug.
$ ```git branch clean_up```

### See branches.
$ ```git branch```

### Switch branches.
$ ```git checkout clean_up```

### Remove files and stage removal.
$ ```git rm '*.txt'```

### Check changes.
$ ```git status```

### Commit changes.
$ ```git commit -m "Remove all the cats"```

### Switch back to master branch.
$ ```git checkout master```

### Merge changes from clean_up branch into master branch.
$ ```git merge clean_up```

### Delete clean_up branch.
$ ```git branch -d clean_up```

### Push to remote repository.
$ ```git push```

## Quick Wins
* **Content**, not files
* **Opt-in**, not opt-out
* **Open**, not locked
* **Distributed**, not centralized
* **Conversations**, not cut-offs
* **People**, not tools
* **Journal**, not backup
* **Anywhere**, not just online

## Fancy
$ ```git log --graph --decorate --abbrev-commit --all --pretty=oneline```

## Cheat
* [Git Workflow and its commands…](http://www.markus-gattol.name/misc/mm/si/content/git_workflow_and_cheat_sheet.png)

## Learn Free
* Git in your browser with [Try Git](http://try.github.com).
* [Pro Git](http://git-scm.com/book) by Scott Chacon is available online.

## Learn More
### Code School
* [Git Real](http://www.codeschool.com/courses/git-real)
* [Git Real 2](http://www.codeschool.com/courses/git-real-2)

## Resources
* http://en.wikipedia.org/wiki/Git_(software)
* http://git-scm.com/
* https://github.com/
* http://www.eliotlash.com/2011/08/processing-for-programmers/

## Next Steps
* https://github.com/b-g/processing-sublime

## Attribution