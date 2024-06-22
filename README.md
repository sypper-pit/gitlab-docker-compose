in `docker-compose.yml` change `domain` and `postgresql password`. 

After start ```docker compose up -d``` use 

```
docker exec -it <id_gitlab_server> cat /etc/gitlab/initial_root_password
```
for get password
