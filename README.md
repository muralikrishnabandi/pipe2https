# zeta-onsite-publisher

## build
```
$ go get github.com/mitchellh/gox
$ gox -arch="amd64"
Number of parallel builds: 3

-->    netbsd/amd64: ...
-->   freebsd/amd64: ...
-->    darwin/amd64: ...
-->   openbsd/amd64: ...
-->     linux/amd64: ...
-->   windows/amd64: ...
```

## usage
```
Usage of ./zeta-onsite-publisher:
  -backlog uint
    	incoming channel capacity (default 8192)
  -backoff duration
    	pause between errors (default 1s)
  -bounces
    	event type: bounces
  -deliveries
    	event type: deliveries
  -fbls
    	event type: fbls
  -other
    	event type: other
  -receptions
    	event type: receptions
  -remote
    	event type: remote
  -transfails
    	event type: transfails
  -transqueue
    	event type: transqueue
  -url string
    	base URL (default "https://zpev.cogolo.net/")
```
