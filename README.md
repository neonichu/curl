# libcurl Swift package

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

Allows using `libcurl` in other Swift packages.

## Usage

```swift
let package = Package(
    name: "example",
    dependencies: [
        .Package(url: "https://github.com/neonichu/curl", majorVersion: 1)
    ]
)
```
