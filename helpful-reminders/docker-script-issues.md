# if running into issues with docker, here are some helpful commands

### if docker container won't run:
go to docker script `/app/bin/init-dev.sh`
(find script by following file path, using `cd` and `ls` -- once you are in the correct file and see the folder, run ` code init-dev.sh` to open the file in vscode)

add to line 3: `tail -f /app/.npmrc`
(that'll print a few lines and then wait forever, so the rest of the script won't run after that line, but it'll let ya debug [eg. with `docker compose exec boop-app bash`])

reminder, once you are done and the container works again, you need to navigate back into the docker script and remove line 3 again

## using terminal in docker container or running 
run `docker compose up -d` -- this will allow me to use terminal in docker container

run `docker compose exec boop-app bash` -- you launch a bash (the default terminal language) prompt inside the container

the next lines you type should start with "root" because you're now in the root file

this is where you can run pnpm commands (i.e. `pnpm install`, `pnpm install ____`, `pnpm clean:all`, etc)