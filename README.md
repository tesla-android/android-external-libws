# wsServer

wsServer - a very tiny WebSocket server library written in C adopted to work in AOSP build system

## Library

wsServer is a tiny, lightweight WebSocket server library written in C that intends
to be easy to use, fast, hackable, and compliant to the
[RFC 6455](https://tools.ietf.org/html/rfc6455).

The main features are:
- Send/Receive Text and Binary messages
- PING/PONG frames
- Opening/Closing handshakes
- Event based (onmessage, onopen, onclose)
- Portability: Works fine on Windows, Linux (Android included), macOS and FreeBSD

