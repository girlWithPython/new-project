1. Create new-project using Explorer
2. Switch to new-project in VS Code Terminal  (cd new-project)
3. Initialize new-project (git init)
4. Open any text editor or notepad
4. Create a new file
5. Save the file as Readme.md in the tadget folder
6. Add Readme.md to the repository so it will be tracked (git add Readme.md)
7. Commit the changes (git commit -m "init")
8. Check that the changes are committed with a commit message successfully ("[main (root-commit) ..hash..] init 1 file changed, 1 insertion(+) create mode ... Readme.md" message in Terminal)
9. Create new branch "development" (git branch development)
10. Switch to the "development" branch (git checkout development)
11. Check that you are successfully switched to the "development" branch ("Switched to branch 'development'" message in Terminal)
12. Add step-by-step instructions to Readme.md and save the changes
13. Add Readme.md to the staging area (git add Readme.md)
14. Commit the changes (git commit -m "first commit") and check that the changes are committed (e.g. look at #8) 
15. Switch to the "main" branch (git checkout main)
16. Merge the changes into "main" branch (git merge development)
17. Push the changes to the remote repository (git push origin main) Commit the changes (git commit -m "first commit") and check that the changes are pushed (e.g. look at #8) 
18. Open "new-project" folder via GitHub
19. Check that the changes from the "development" branch are merged into the "main" branch successfully by comparing the content of Readme.md with the changes   