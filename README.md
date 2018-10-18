# Alpine image with tools

Includes `bind-tools`, `coreutils`, `curl`, `fish`, `git`, `jq`, `mtr`, `netcat-openbsd`, `openssh`, `openssl`, `tmux` and `tree`. Please create a pull request to add other useful (small) tools.

```bash
docker run -ti digitorus/alpine-tools sh
```
Reconnect
```bash
docker ps -a
docker start {container id}
docker attach {container id}
```
