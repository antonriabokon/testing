##  Task steps
1. Boot your laptop.
2. Open your browser.
3. Go to GitHub web page(https://github.com/"yourusername").
4. Press "Repository".
5. Press green button "New".
6. Create a new name for your repository.
7. Press "Create repository".
8. Follow GitHub instructions.
9. Fill down README.md file.
10. Open your "test folder" in Visual Studio.
11. Right click on README.md, Open in integrated terminal.
12. Run next commands one by one: git add README.md, git commit -m "your message", git push origin "your branch".
13. If everything is ok, check your remote repository.
14. Make some changes in README.md in your remote repository.
15. Open VSC and make changes in README.md in your local repository, save it and do again step 12.
16. You have an error, it occurs when you made changes in your remote repository which your local repository does not have.
17. Run next command in VSC: git pull origin "your branch"
18. Now you are provided with three choices:

* git pull --no-rebase origin "your branch" - Merge (default behavior): If you want to merge the remote changes into your local branch (which is common if you've made some local changes and just want to bring in the remote changes)

* git pull --rebase origin "your branch" - Rebase (rewrite history): If you want to rebase your local changes on top of the remote ones (this will rewrite the history, which can make things cleaner)

* git pull --ff-only origin "your branch" - Fast-forward only (no merge, no rebase): If you only want to allow a fast-forward merge (meaning the remote branch must be ahead of your local branch with no divergence)

19. Run prefered by you command.
20. In case of further conflicts you can also try to: git add "conflict file name", but this time without commit.
21. Then run git rebase --continue.
22. If everything is ok, git push origin "your branch".
23. Check if everything is ok, in case of emergency or other errors please find me in Discord, mynickname.