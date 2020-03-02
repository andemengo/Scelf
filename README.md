# Scelf

<p align="center">
    <img src="/GitHub%20Page/Images/logo.svg?sanitize=true" width="250">
</p>

![License](https://img.shields.io/github/license/andemengo/Scelf)
![Platforms](https://img.shields.io/badge/platform-iOS%20%7C%20macOS%20%7C%20tvOS%20%7C%20watchOS-lightgrey)

Put some Romagna in your code.

## How to use

In every class conform to `protocol Scelf` finally you can use `scelf` instead `self`.

```swift
protocol Scelf {
    typealias scelf = Self
}
```

## License
Scelf is released under the Unlicense license. [See LICENSE](https://github.com/andemengo/Scelf/blob/master/LICENSE) for details.
