merge-branches

### MERGE TEST
 `git init`
 `touch index.html`
 `git add .`
 `git commit -m "added files"`
  GITHUB: Create a new repository called merge-test
 `git remote add origin https://myRepository`
 `git push --set-upstream origin main`
 `git branch myBranch`
 `git switch myBranch`
 add `<p>Hello World!</p>` to the index.html file
 Save the changes CTRL + S
 `git add .`
 `git commit -m "updated file`
 `git switch main`
 Change the history from `Auto` to `All`
16. `git merge myBranch`
17. `git push`
18. `git switch myBranch`
19. Add `<p> Amazing World!</p>` to index.html file
20. Save the changes CTRL + S
21. `git add .`
22. `git commit -m "updated file"`
23. `git switch main`
24. Add the file about.html with `touch about.html`
25. `git add .`
26. `git commit -m "added a file"`
27. `git merge myBranch`
28.  Approve the merge by closing the merge editor or the VIM editor by typing `:qa` then `enter`
29. `git rebase myBranch`
30. `git push`
31. `git switch myBranch`
32. `git rebase main`