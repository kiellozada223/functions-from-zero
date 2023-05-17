[![Python application test with Github Actions](https://github.com/kiellozada223/functions-from-zero/actions/workflows/main.yml/badge.svg)](https://github.com/kiellozada223/functions-from-zero/actions/workflows/main.yml)

# functions-from-zero
live training

### To call Microservice

something like this
```bash
curl -X 'POST' \
  'https://kiellozada223-verbose-telegram-wp97pwj7r47c5pqv-8080.preview.app.github.dev/wiki' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Microsoft"
}'
```


### Build Container

`docker build .`
`docker image ls`