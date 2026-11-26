# Trackon Client

## Overview

Trackon Client is a GPS tracking app for Android and iOS. It runs in the background and sends location updates to your Trackon server. The server is compatible with the Traccar protocol and API.

- **Real-time Tracking**: See your device’s location on your private server in real time.
- **Open-Source**: 100% free and open-source, with no ads or tracking.
- **Customizable**: Configure update intervals, accuracy, and data usage to fit your needs.
- **Privacy First**: Your location data is sent only to your chosen server—never to third parties.
- **Easy Integration**: Designed to work with Trackon and compatible GPS tracking servers.

Just enter your server address, grant location permissions, and the app will automatically send periodic location reports in the background.

By default, the client sends GPS updates to `https://trackon.imaxprojects.com/`.
TrackOn forwards client updates internally to the OsmAnd protocol. To use a
different server, change the address in the app settings.

| Client App |
|---|
| <img src=".github/screenshot.png" alt="Trackon Client app" width="200"> |

## Build

Requires Flutter 3.50.1 or later (Dart 3.13 or later).

```shell
flutter pub get
flutter run
```

## Team

- Anton Tananaev ([anton@traccar.org](mailto:anton@traccar.org))

## License

Apache License, Version 2.0. See [LICENSE.txt](LICENSE.txt) for details. Trackon Client is derived from the Traccar Client project.
