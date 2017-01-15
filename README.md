
## GIT quick statistics

> Git-quick-stats is a simple and efficient way to access various statistics in git repository.

![screenshot_example](https://cloud.githubusercontent.com/assets/6382002/21964569/946c0042-db4e-11e6-8a2a-aa20f0b71b04.png)

Want to contribute? Great! First, [read this page][].


## Usage

```
git-quick-stats
```

## Installation

```
# depencences:
$ apt-get install dialog

# clone & install
$ git clone https://github.com/arzzen/git-quick-stats.git && cd git-quick-stats
$ sudo make install
```

For uninstalling, open up the cloned directory and run

```
sudo make uninstall
```

## Contribution 

Want to contribute? Great! First, read this page.

#### Code reviews
All submissions, including submissions by project members, require review. 
We use Github pull requests for this purpose.

#### Some tips for good pull requests:
* Use our code
  When in doubt, try to stay true to the existing code of the project.
* Write a descriptive commit message. What problem are you solving and what
  are the consequences? Where and what did you test? Some good tips:
  [here](http://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message)
  and [here](https://www.kernel.org/doc/Documentation/SubmittingPatches).
* If your PR consists of multiple commits which are successive improvements /
  fixes to your first commit, consider squashing them into a single commit
  (`git rebase -i`) such that your PR is a single commit on top of the current
  HEAD. This make reviewing the code so much easier, and our history more
  readable.

#### Formatting

This documentation is written using standard [markdown syntax](https://help.github.com/articles/markdown-basics/). Please submit your changes using the same syntax.

## Licensing
MIT see [LICENSE][] for the full license text.

   [read this page]: http://github.com/arzzen/git-quick-stats/blob/master/CONTRIBUTING.md
   [landing page]: http://arzzen.github.io/git-quick-stats
   [LICENSE]: https://github.com/arzzen/git-quick-stats/blob/master/LICENSE.txt
