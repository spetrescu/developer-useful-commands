# developer-useful-commands

1. Create tar archive: `tar -czvf LotsOfFiles.tgz LotsOfFiles`
2. Uncompress tar archive: `tar -xvf LotsOfFiles.tgz`
3. Delete all files with specific extension in dir: `find . -name "*.DS_Store" -type f -delete`
4. List all files with specific extension in dir: `find . -name "*.DS_Store" -type f`
5. List all directories that contain specific character (underscore in this case): `find . -name '*_*' -type d`
6. Remove docker image: `sudo docker rmi -f <IMAGE ID>`
7. Stop process for docker container `docker rm name_of_the_docker_container`
8. `git reset --hard origin/main`
9. Stage only deleted files git: `git ls-files --deleted | xargs git add`
10. Get vim on ubuntu machine: `apt-get update && apt-get install apt-file -y && apt-file update && apt-get install vim -y`
11. List files changed in commit (by hash): first `git log` and then `git show --pretty="" --name-only <hash>`
12. Undo last commit from local: `git reset --soft HEAD~1`
13. Undo last commit from remote: first `git reset HEAD^` and then `git push origin +HEAD`
14. Restore uncommited deleted file: first `git reset HEAD <file>` and then `git checkout -- <file>`
15. List all conda created on system: `conda env list`
16. Find text in dirs: `grep -rnw '/path/to/somewhere/' -e 'pattern'`
17. Display all available GPUs: `lspci -k|grep -iA2 "VGA"`
18. List all of your conda environments: `conda info --envs`
19. Disable conda on startup: `conda config --set auto_activate_base false`
20. Discard local changes on one file: `git checkout -- <file>`

### Contributions
Feel free to open a PR in case you want to add other useful commands.
