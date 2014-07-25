#git-feature-branch

Start a feature branch that will cleanly merge to other branches

##Usage

`git feature-branch <new_feature> [<upstream>...]`

Creates a new branch `<new_feature>` from the common ancestor of all `<upstream>` branches. `<new_feature>` will cleanly merge to all `<upstream>` branches.

If `<upstream>` is not specified it will default to origin/master.

`<upstream>...` can be configured with: `git config feature-branch.upstreams`

##Install

Download and put somewhere in your $PATH

For those with [homebrew](http://brew.sh/) `brew install sheldon/git-feature-branch/git-feature-branch`
