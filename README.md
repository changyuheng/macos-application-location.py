# macos-application-location

This tiny package helps you to obtain the path of an Application (.app) that the current process is running from on macOS.

## Installation

```sh
pip install macos-application-location
```

## Usage

```py
import pathlib

import macos_application_location


app_path: pathlib.Path = macos_application_location.get()
```

## Reference

1. [App Translocation Notes](https://developer.apple.com/forums/thread/724969)
