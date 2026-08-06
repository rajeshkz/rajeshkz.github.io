# rajeshkz.github.io

## Random Git commands
Simple case (assuming main's .github has nothing extra beyond what's on multi-tenancy):
Below  restores files (__Only restore files/folders named .github__) from the multi-tenancy branch into your current working directory (ie main branch currently).
```
git switch main
git restore --source=multi-tenancy --worktree -- .github
# review, then:
git add .github
git commit -m "Sync .github from multi-tenancy"
```
Global Traceroute used for debugging when the server is not reachable
https://globalping.io/cli
