# [rclone-sync](https://github.com/ishbguy/rclone-sync)

[![Version][versvg]][ver] [![License][licsvg]][lic]

[versvg]: https://img.shields.io/badge/version-v0.1.0-lightgrey.svg
[ver]: https://img.shields.io/badge/version-v0.1.0-lightgrey.svg
[licsvg]: https://img.shields.io/badge/license-MIT-green.svg
[lic]: https://github.com/ishbguy/rclone-sync/blob/master/LICENSE

A bidirectional sync tool using rclone and implemented in shell.

## Table of Contents

+ [:art: Features](#art-features)
+ [:straight_ruler: Prerequisite](#straight_ruler-prerequisite)
+ [:rocket: Installation](#rocket-installation)
+ [:memo: Configuration](#memo-configuration)
+ [:notebook: Usage](#notebook-usage)
+ [:hibiscus: Contributing](#hibiscus-contributing)
+ [:boy: Authors](#boy-authors)
+ [:scroll: License](#scroll-license)

## :art: Features

+ What an amazing thing!

## :straight_ruler: Prerequisite

> + `bash`
> + `rclone`
> + `realpath`

## :rocket: Installation

```
$ git clone https://github.com/ishbguy/rclone-sync
$ export PATH="$PATH:$(pwd)/rclone-sync"
```

## :memo: Configuration

There is no configuration for rclone-sync, but you need to configure rclone if
you want to use your cloud service. For detail rclone configuration, you can
type `man rclone` in a shell or go to [rclone homepage](https://rclone.org/).

## :notebook: Usage

Simply run:
```
rclone-sync.sh path1 path2
```
Just looking what will happen (dry run):
```
rclone-sync.sh -d path1 path2
```
For help:
```
rclone-sync.sh -h
```

## :hibiscus: Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## :boy: Authors

+ [ishbguy](https://github.com/ishbguy)

## :scroll: License

Released under the terms of [MIT License](https://opensource.org/licenses/MIT).
