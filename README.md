#git-feature-branch

Start a feature branch that will cleanly merge to other branches

##Usage

`git feature-branch <new_feature> [<upstream>...]`

Creates a new branch `<new_feature>` from the common ancestor of all `<upstream>` branches. `<new_feature>` will cleanly merge to all `<upstream>` branches.

If `<upstream>` is not specified it will default to origin/master.

`<upstream>...` can be configured with: `git config feature-branch.upstreams`

##Install

1. `sudo wget https://raw.githubusercontent.com/sheldon/git-feature-branch/v0.3.1/git-feature-branch > /usr/local/bin/git-feature-branch`

Or for those with [homebrew](http://brew.sh/)

1. `brew install sheldon/git-feature-branch/git-feature-branch`
