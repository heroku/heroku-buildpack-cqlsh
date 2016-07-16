# cqlsh buildpack

## why?

Private spaces

## how?

```bash
heroku buildpacks:add https://github.com/heroku/heroku-buildpack-cqlsh
```

## assumptions

- You have heroku-cassandra installed and attached as `CASSANDRA`

## running

You can either use `run:inside` or plain 'ol `run`:

```bash
heroku run:inside -a <app> <process> cqlsh
```
