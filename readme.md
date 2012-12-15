## testing log shuttle

Get a logplex token.

```bash
$ heroku sudo info -x -a myapp
```

Start log-shuttle.

```bash
$ ./start your-log-token
```

Use sample logs to feed the shuttle.

```bash
$ ./sample-logs | nc -U /tmp/log-shuttle
```
