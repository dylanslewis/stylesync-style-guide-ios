# Style Guide

An iOS app to showcase generated style files from [`stylesync`](https://github.com/dylanslewis/stylesync).

<p align="center">
<img src="Design/Hero.png" width="1000" max-width="90%" alt="stylesync" />
</p>

## How to use

You can install `stylesync` using the [Swift Package Manager](https://github.com/apple/swift-package-manager):
```
$ git clone https://github.com/dylanslewis/stylesync.git
$ cd stylesync
$ swift build -c release -Xswiftc -static-stdlib
$ cp -f .build/release/stylesync /usr/local/bin/stylesync
```

Since this project already has a `stylesyncConfig.json` file, after installing you can just run `stylesync` to update to the latest styles in [`Sample.sketch`](Design/Sample.sketch).

Due to security reasons, the `gitHubPersonalAccessToken` is not included in `stylesyncConfig.json`, so **stylesync** will *not* commit changes or generate a pull request if you run the script. An example Pull Request is available [here](https://github.com/dylanslewis/stylesync-style-guide-ios/pull/4).

[![Vimeo](Design/Vimeo.png)](https://vimeo.com/243729044)
