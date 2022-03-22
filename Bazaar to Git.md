## Bazaar to Git

To convert a Bazaar branch to Git, open a Bazaar branch of your project and do the following:



```shell
git init                                        # Initialise a new git repo
bzr fast-export --plain . | git fast-import     # Import Bazaar history into Git
```



Now you should have all the revision history for that Bazaar branch in Git:



```shell
git log  # Check your revision history is in Git
```



(From [Astrofloyd’s blog](http://astrofloyd.wordpress.com/2012/09/06/convert-bzr-to-git/))

----

## [Convert bzr to git](https://astrofloyd.wordpress.com/2012/09/06/convert-bzr-to-git/)

Posted on [6 September 2012](https://astrofloyd.wordpress.com/2012/09/06/convert-bzr-to-git/) by [AstroFloyd](https://astrofloyd.wordpress.com/author/astrofloyd/)

I played with bzr (Bazaar) as a source-control manager (SCM) for a while, after having used svn for a couple of years. In the end, bzr turned out to be the stepping stone I needed to move to git. Hence, I started converting my repositories from bzr to git. Here’s how it’s easily done.



For this method, you’ll need to install the package [bzr-fastimport](https://launchpad.net/bzr-fastimport) to export data from your bzr repository. Gentoo users emerge dev-vcs/bzr-fastimport. Before you start, make sure you committed all your changes, e.g. using `bzr st` and `bzr diff`.

Then:

```
  cp -pr repo-dir repo-dir_backup                 # Make a backup
  cd repo-dir                                     # Change into your dir
  git init                                        # Initialise a new git repo
  bzr fast-export --plain . | git fast-import     # Do the actual conversion
  git co -f master                                # Will reply 'Already on master'
  rm -rf .bzr/                                    # Remove the bzr data
```

Verify that everything is there (e.g. using diff -r repo-dir repo-dir_backup) before you delete the backup directory. You’re all set.