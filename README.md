# docker-httpd-ssi
Docker build for SSI-enabled Apache 2.4 Alpine

## Usage

### build

```
docker build -t nnasaki/httpd-ssi .
```

### run

Example for show current directory.

```
docker run --rm -p 10080:80 --name httpd-ssi -v "$PWD":/usr/local/apache2/htdocs/ nnasaki/httd-ssi
```

You can see server include files.
