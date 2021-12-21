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
