# libcurl Swift package

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
