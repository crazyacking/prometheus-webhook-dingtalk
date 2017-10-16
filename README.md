# prometheus-webhook-dingtalk

Generating [DingTalk] notification from [Prometheus] [AlertManager] WebHooks.

## Build

Just type and run: `make build`, all binaries will be placed into `.build' directory.

## Usage

```
usage: prom-webhook-dingtalk [<args>]


   -web.listen-address ":8060"
      Address to listen on for web interface.

 == DING ==

   -ding.profile
      Custom DingTalk profile (can specify multiple times, <profile>=<dingtalk-webhook-url>).

   -ding.timeout 5s
      Timeout for invoking DingTalk webhook.
```

[Prometheus]: https://prometheus.io
[AlertManager]: https://github.com/prometheus/alertmanager
[DingTalk]: https://www.dingtalk.com