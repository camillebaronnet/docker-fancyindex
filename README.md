# http-directory-index

Http-directory-index is a Docker image that allows you to create easy web access to files.

## Installation

### Using Apaxy

```bash
docker run -v /your/files/path:/var/www/data -p 8000:80 camillebaronnet/http-directory-index:apaxy
```

### Using Fancin

```bash
docker run -v /your/files/path:/var/www/data -p 8000:80 camillebaronnet/http-directory-index:fancin
```
