# Updated for FireOS
Updated for FireOS 6. Tested with FireTV 4k Stick. No root etc needed. Download APK from releases and sideload it.

Once it is connected to the correct network, and it should auto-connect to the WPA2 Enterprise Network on bootup. Though you may have to delete the old saved Wifi networks from Network settings. Should be no need to keep the APK installed once that is done.

Should also work with Android TVs and is compatible with the remote

# Installing certificate on FireOS

Archive.org - https://web.archive.org/web/20210508193836/http://www.unibia.com/unibianet/systems-networking/install-additional-tls-root-cas-amazon-fire-tv

Guide - http://www.unibia.com/unibianet/systems-networking/install-additional-tls-root-cas-amazon-fire-tv

# Enterprise Wi-Fi
Android TV does not by default have a user interface for setting up Enterprise Wi-Fi networks. These networks, use the [Extensible Authentication Protocol (EAP)](https://en.wikipedia.org/wiki/Extensible_Authentication_Protocol), a framework for authenticating your device with the Wi-Fi network by providing both a username and password.

These types of networks are common at businesses, where only particular users should be accessing the network, or at universities where content is audited.

As stated above, though there is no user interface for connecting to these networks, the system has APIs for programmatically connecting. To aid those in the situations above, this app provides a useful interface for making connections.

There is another app that fulfills this need on Android TV, although I have found a number of issues with how it works.

## Features
* Connection details can be saved and updated
* Automatically fills in fields where possible
* Shows logs of connection status to show you progress is happening
* Can display a QR code of the network to connect your other devies

<img src='https://github.com/ITVlab/Enterprise-Wi-Fi/blob/master/promo/device-2016-09-07-012808.png?raw=true' />

<img src='https://github.com/ITVlab/Enterprise-Wi-Fi/blob/master/promo/device-2016-09-07-012756.png?raw=true' />
