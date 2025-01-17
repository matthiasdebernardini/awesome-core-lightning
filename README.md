
# Awesome Core Lightning

A curated list of awesome [core-lightning][cln] projects and plugins

## Plugins

* [Community curated plugins for Core-Lightning.][lightningd-plugins]
* [Circular][circular] - Plugin that helps routing nodes rebalance their channels

## Dev Tools

### RPC

There are a few ways to do RPC on your lightning node. There is commando (new in v0.12.0) which allows you to call jsonrpc methods over lightning TLVs. You can use [lnsocket][lnsocket] to establish lightning connection from any application to call these RPCs.

There is also gRPC and REST methods methods as well.

* [Rune Workshop][rune-workshop] - A web UI for constructing commando auth runes
* [c-lightning-REST][cln-rest] - REST APIs for c-lightning written with node.js

### Libraries

* [lnsocket][lnsocket] - A C/JS library for talking to lightning nodes and calling commando RPCs
* [rune-decoder][rune-decoder] - JS library for decoding runes

## Apps

* [lnlink][lnlink] - An applepay-like iOS app for controlling a CLN node remotely via commando
* [Payment Links][payment-links] - Create self-contained product payment links that work with any CLN node
* [sendsats.lol][sendsats] - Get a lightning address for your CLN node. Powered by commando!



[cln]: https://github.com/ElementsProject/lightning
[lnlink]: https://lnlink.app
[rune-decoder]: https://github.com/clams-tech/rune-decoder
[payment-links]: http://lnlink.org
[circular]: https://github.com/giovannizotta/circular
[cln-rest]: https://github.com/Ride-The-Lightning/c-lightning-REST
[lightningd-plugins]: https://github.com/lightningd/plugins
[lnsocket]: https://github.com/jb55/lnsocket
[rune-workshop]: https://jb55.com/runes
[sendsats]: https://sendsats.lol
