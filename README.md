# learn-merge-conflict

An exercise repository for [ComputeSphere Learn](https://learn.computesphere.com), *Application foundations*:

- **2.6.3 Try it: branch, commit, resolve a conflict.** Clone it, merge `friendly-greeting` into `main`, and resolve the conflict by hand.
- **2.7.3 Try it: open and merge a pull request.** Fork it (with all branches), open a pull request from `friendly-greeting` into your fork's `main`, and resolve the conflict on GitHub.

`main` and `friendly-greeting` both change the same line of `greeting.js`, so they conflict on purpose. Print the greeting with:

```bash
node -e "console.log(require('./greeting'))"
```
