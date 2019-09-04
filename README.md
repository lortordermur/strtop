**strtop** – a 'top' for Syncthing relay servers


### Summary ###

`strtop` displays continual statistics about a Syncthing relay, as well as a
throughput history graph. It should be able to run fine on most Unix/Linux
shells provided the dependencies are met:

* **jq**[[1]] (JSON parser)
* **tput** (part of the `ncurses-bin` package)
* **curl** (preinstalled on most systems)
* **bc** (preinstalled on most systems)


### Installation ###

Obtain the aforementioned dependencies as required. Then copy the `strtop`
script to somewhere in your path, like `~/.bin`. Symlinking works too.


### Usage ###

    strtop [relayserver] [relayport]

`relayserver` is the network name or IP address of the relay and defaults to
'localhost'. `relayport` defaults to 22070.


[1]: https://stedolan.github.io/jq/
