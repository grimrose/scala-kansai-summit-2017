# scala-kansai-summit-2017

## Akka Streamsへ移行しとるんやけどちょっと聞いてや

### requirements

docker
docker-compose

### usage

```sh
docker-compose up
```

### setup

install [RISE](https://github.com/damianavila/RISE)

```sh
pip install RISE
```

install jupyter-nbextension

```sh
jupyter-nbextension install rise --py --sys-prefix
```

enable jupyter-nbextension

```sh
jupyter-nbextension enable rise --py --sys-prefix
```

notebookをreloadして有効にする
