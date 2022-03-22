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
12. Undo last commit: `git reset --soft HEAD~1`

## Jupyter notebook env Ubuntu for specific Python version
1. `sudo add-apt-repository ppa:deadsnakes/ppa`
2. `sudo apt-get update`
3. `sudo apt-get install python3.7`
4. `python3.7 -m pip install virtualenv`
5. `python3.7 -m virtualenv my-37-venv`
6. `source my-37-venv/bin/activate`
7. `pip install jupyter`
8. `ipython kernel install --name "my-37-env-kernel" --user`
9. `pip install jupyterlab`
11. `python -m jupyterlab`

## CYGWIN 
This is a test.

