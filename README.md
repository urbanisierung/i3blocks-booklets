# i3blocks-booklets

Collection of some custom [i3blocks](https://github.com/vivien/i3blocks) booklets.

## github_prs

See open PRs in your status bar:

`${repo} ${reviewable PRs}/${all PRs}`

* repository
* count of open PRs (not `WIP` or `HOLD`)
* count of all open PRs

![i3bar](./media/i3bar-github-pr-short.png)

### Installation

* Install [hub cli](https://github.com/github/hub)
* Copy [`github_prs`](./github_prs) to your booklet folder
* Update path to github credentials in `github_prs`

In your `i3blocks.conf` add

```bash
[github_prs]
label=your-label-for-repo
instance=path-to-repository
interval=60 # or your preferred interval
```
