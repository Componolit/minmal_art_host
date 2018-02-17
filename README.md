# ART on Linux x86_64 host

This is a minmal Manifest for building Android's ART on Linux x86_64 systems.
To build it, follow the usual Android process:

    $ mkdir mah
    $ cd mah
    $ repo init -u https://github.com/Componolit/minmal_art_host.git --depth=1
    $ repo sync -c
    $ make build-art-host
