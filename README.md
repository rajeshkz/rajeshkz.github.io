# rajeshkz.github.io

## Random Git commands
Simple case (assuming main's .github has nothing extra beyond what's on multi-tenancy):
```
git switch main
git restore --source=multi-tenancy --worktree -- .github
# review, then:
git add .github
git commit -m "Sync .github from multi-tenancy"
```
