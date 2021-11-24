# Coder-Compose

To Run A Docker Based Code-Server For Raspberry Pi (4B)  
( Because there's only a `Dockerfile.armhf` )

## Usage

`docker-compose up -d`

`docker exec -it code-server /bin/bash`

`docker logs -f code-server`

Access to the code-server at `http://<your-ip>:8443`

### Params

#### Mods

+ `linuxserver/mods:code-server-golang`

+ `linuxserver/mods:code-server-nodejs`

+ `linuxserver/mods:code-server-python3`

```bash
DOCKER_MODS=linuxserver/mods:code-server-golang|linuxserver/mods:code-server-nodejs|linuxserver/mods:code-server-python3
```

#### Secrets

```bash
FILE__PASSWORD=/run/secrets/mysecretapssword
```

## TODO
