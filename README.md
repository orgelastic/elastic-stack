# Elastic Stack For Circle

Only use this for development purpose

### Usage

Change password in the .env file

```
ELASTIC_PASSWORD=changeme
```

Run the docker-compose file

```bash
docker-compose up -d
```

You might need the CA crt file for authentication

```bash
docker exec -it circle-es01-1 sh

cd /usr/share/elasticsearch/config/certs/ca

cat ca.crt
```