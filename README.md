# **stylesync** Style Guide (iOS)

An iOS app to showcase generated style files from [`stylesync`](https://github.com/dylanslewis/stylesync).

## How to use

You can install `stylesync` using the [Swift Package Manager](https://github.com/apple/swift-package-manager):
```
$ git clone https://github.com/dylanslewis/stylesync.git
$ cd stylesync
$ swift build -c release -Xswiftc -static-stdlib
$ cp -f .build/release/stylesync /usr/local/bin/stylesync
```

Since this project already has a `stylesyncConfig.json` file, after installing you can just run `stylesync` to update to the latest styles in [`Sample.sketch`](Design/Sample.sketch).

`// TODO: Add speed run video`
