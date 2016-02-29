[![Travis](https://img.shields.io/travis/beevelop/docker-rabbitmq-stomp.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-rabbitmq-stomp)
[![Docker Pulls](https://img.shields.io/docker/pulls/beevelop/rabbitmq-stomp.svg?style=flat-square)](https://links.beevelop.com/d-rabbitmq-stomp)
[![ImageLayer](https://badge.imagelayers.io/beevelop/rabbitmq-stomp:latest.svg)](https://imagelayers.io/?images=beevelop/rabbitmq-stomp:latest)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# RabbitMQ with support for [STOMP](https://stomp.github.io/) and [SockJS](https://github.com/sockjs) for Docker :whale:

```
docker run -d --name rabbit-stomp -p 15674:15674 beevelop/rabbitmq-stomp
```

By default the Web STOMP plugin exposes both a WebSocket and a SockJS endpoint on port 15674. The WebSocket endpoint is available on the /ws path:
```
http://127.0.0.1:15674/ws
```
The SockJS endpoint on the /stomp prefix:
```
http://127.0.0.1:15674/stomp
```

Please refer to the [RabbitMQ Web-Stomp Plugin documentation](https://www.rabbitmq.com/web-stomp.html#usage) for detailed usage instructions.

## [STOMP-UI](https://beevelop.github.io/stomp-ui/)
Use the [STOMP-UI](https://beevelop.github.io/stomp-ui/) to play around with your RabbitMQ installation.
