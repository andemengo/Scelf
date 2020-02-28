# Scelf

<p align="center">
    <img src="/GitHub%20Page/Images/logo.svg?sanitize=true" width="250">
</p>

Put some Romagna in your iOS code.

In every class conform to `protocol Scelf` finally you can use `scelf` instead `self`.

```swift
protocol Scelf {
    typealias scelf = Self
}
```
