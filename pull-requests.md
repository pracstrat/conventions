# Pull Requests

## Resolve an issue

* Open Github, find the issue, assign to yourself.
* `$(master) git pull` - Pull latest codebase.
* `$(master) git checkout -b NEW_BRANCH` - Create a new
branch. (Ex. `43-broken-login-page`)
* Start doing changes.
* `$(NEW_BRANCH) git add FILES` - Add modified files.
* `$(NEW_BRANCH) git commit -m 'DESCRIPTIVE_MESSAGE'` - Commit changes.
* After you finish that. `$(NEW_BRANCH) git push` - Push to
default remote `origin`.
* Send a Pull Request on GitHub. Or use
[Hub](https://github.com/defunkt/hub). Title 'Fixes broken login page'.
* Write logs on AC.

### If it protract over into the next day

* Send a Pull Request, and prefix the title with `[WIP]`. - Ex. `[WIP]
Fixes broken login page`

