
# go-log

  Oh, yes, another logging library.

  Born as a fork of http://godoc.org/github.com/segmentio/go-log

  Simple printf-style logger which is more or less the same as Go's core
  logger with log levels.

  View the [docs](http://godoc.org/github.com/daddye/go-log).

## Example

```go
log.Debug("something")
log.Emergency("hello %s %s", "tobi", "ferret")

l := log.New(os.Stderr, DEBUG, "")
l.Debug("something happened")
l.Info("hello %s", "Tobi")
l.Error("boom something exploded")
```

## License

 MIT
