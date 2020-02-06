# nginx-plus

Docker image based on the instructions for test Nginx Plus.

You need the files in root of this project:

* nginx-repo.key

* nginx-repo.crt

Get these files in https://www.nginx.com/free-trial-request/

## Instructions

```bash
git clone git@github.com:ripper2hl/nginx-plus.git

cd nginx-plus

cp /Example/Directory/nginx-repo.crt .

cp /Example/Directory/nginx-repo.key .

docker build . -t nginx-plus

docker run -p 8080:80 nginx-plus
```

## Example

[![asciicast](https://asciinema.org/a/JGDwTbGlNNWllCoUpCTS7w68C.svg)](https://asciinema.org/a/JGDwTbGlNNWllCoUpCTS7w68C)
