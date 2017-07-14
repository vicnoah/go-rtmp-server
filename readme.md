# Golang rtmp server demo

This is a very tiny demo with rtmp protocol server/client side implement.

## Requirement

You need golang to build all tools. 

## Install

```bash
go get -u -v github.com/netroby/go-rtmp-server

~/go/bin/go-rtmp-server
```


## Usage


now you can using obs to push stream to rtmp server


the stream url maybe ```rtmp://your.domain.host/live```

Now you may visit the demo at 
```
http://your.domain.host:8089/
```