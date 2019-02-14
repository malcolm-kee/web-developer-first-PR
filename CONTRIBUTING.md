# Contributing

Thanks for being willing to contribute!

## Project setup

1. Fork and clone the repo
1. Create a branch for your PR
1. Add a html file in the `pages` folder with your name, e.g. `malcolm-kee.html`
1. Add a link to your page in `index.html`
1. Create a Pull Request

> Tip: Keep your `master` branch pointing at the original repository and make
> pull requests from branches on your fork. To do this, run:
>
> ```
> git remote add upstream https://github.com/downshift-js/downshift.git
> git fetch upstream
> git branch --set-upstream-to=upstream/master master
> ```
>
> This will add the original repository as a "remote" called "upstream," Then
> fetch the git information from that remote, then set your local `master`
> branch to use the upstream master branch whenever you run `git pull`. Then you
> can make all of your pull request branches based on this `master` branch.
> Whenever you want to update your version of `master`, do a regular `git pull`.
