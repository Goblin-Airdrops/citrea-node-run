# citrea-node-run

The easiest way to run a Citrea Full Node is to use the docker-compose.yml

 # Step 1:

 create a directory and clone the compose file in it:
```console
mkdir citrea
cd citrea
```

```console
curl https://raw.githubusercontent.com/chainwayxyz/citrea/nightly/docker-compose.yml --output docker-compose.yml
```
# Step 2:

run the container in detached mode:

```console
docker-compose -f docker-compose.ym up -d
```
