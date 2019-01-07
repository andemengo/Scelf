# Scelf

<img src="/Images/RomagnaFlag.png" width="300">

Put some Romagna in your iOS code.

In every class conform to `protocol Scelf` finally you can use `scelf` instead `self`.

```swift
protocol Scelf {
    typealias scelf = Self
}

```
