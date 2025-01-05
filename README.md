# iotup.github.io
IoTUp Website

# Running the web server locally
To run the webserver locally, execute the following docker command:
```sh
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs $(docker build -q ./container)
```
