# nginx-elk-log

Simple implementation bsased on: https://rzetterberg.github.io/nginx-elk-logging.html


## How to run:
```
docker-compose build && docker-compose up
```

## Another infos:

### Change Log Attributes:
Replace `log_format` in 
``
nginx/conf/nginx.conf
``
with your log format.

Don't forget to change `grok pattern` in
``
logstash/conf/patterns/
``
based on log format above.
