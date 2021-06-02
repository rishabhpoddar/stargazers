## Installation:

```
./init.sh
```
- Be sure to change the `GOPATH` var in the `init.sh` script to point to the `cmd` dir in this dir

## Fetch data:

```
export GOPATH=<location to this dir>/cmd && go run main.go fetch --repo=:owner/:reponame --token=<github access token>
```

## Analyse data:
```
export GOPATH=<location to this dir>/cmd && go run main.go analyze --repo=:owner/:reponame
```