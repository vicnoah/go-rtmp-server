# Golang rtmp server demo

##　Requirement

You need golang to build all tools. 

The http server we need Caddy.

## Install

```bash
go get -u -v github.com/mholt/caddy/caddy 
go get -u -v github.com/netroby/go-rtmp-server

cd ~/go/src/github.com/netroby/go-rtmp-server

cd www && ./go/bin/caddy

~/go/bin/go-rtmp-server
```


## Usage


now you can using obs to push stream to rtmp server


the stream url maybe ```rtmp://your.domain.host/live```

Remember change www/index.html, 

set url to 
```
url: 'http://your.domain.host:8089/live'
```