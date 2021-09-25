# coder-compose

## Usage

`docker-compose up -d`

`docker exec -it code-server /bin/bash`

`docker logs -f code-server`

Access to the code-server at `http://<your-ip>:8443`

### Parameters

#### Mods

`DOCKER_MODS=linuxserver/mods:code-server-golang|linuxserver/mods:code-server-nodejs|linuxserver/mods:code-server-python3`

#### Secrets

```bash
-e FILE__PASSWORD=/run/secrets/mysecretapssword
```

## TODO
