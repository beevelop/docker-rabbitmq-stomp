[![Travis](https://shields.beevelop.com/travis/beevelop/docker-rabbitmq-stomp.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-rabbitmq-stomp)
[![Pulls](https://shields.beevelop.com/docker/pulls/beevelop/rabbitmq-stomp.svg?style=flat-square)](https://links.beevelop.com/d-rabbitmq-stomp)
[![Layers](https://shields.beevelop.com/docker/image/layers/beevelop/rabbitmq-stomp/latest.svg?style=flat-square)](https://links.beevelop.com/d-rabbitmq-stomp)
[![Size](https://shields.beevelop.com/docker/image/size/beevelop/rabbitmq-stomp/latest.svg?style=flat-square)](https://links.beevelop.com/d-rabbitmq-stomp)
[![Release](https://shields.beevelop.com/github/release/beevelop/docker-rabbitmq-stomp.svg?style=flat-square)](https://github.com/beevelop/docker-rabbitmq-stomp/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# RabbitMQ with support for [STOMP](https://stomp.github.io/) and [SockJS](https://github.com/sockjs)

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
