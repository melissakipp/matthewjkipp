# WordPress and Docker

## Start project:

```sh
$ docker compose up
```

- `-d` flag will run docker in detached mode

Next after starting container:

- Go to `http://localhost:8000` to setup and install WordPress

### Clean up at the end of the project

```sh
$ docker compose down -v --rmi all
```

- `-v` flag will remove volume
- `--rmi all` flag will remove _all_ images.

#### Resource

[Docker Env - Brad Traversy](https://gist.github.com/bradtraversy/faa8de544c62eef3f31de406982f1d42)
