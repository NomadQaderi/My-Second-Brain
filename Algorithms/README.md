# What is Big O Notation?

Big O notation (aka Big O) is a way assessing the relative performance of a data structure or algorithm usually along two axis: time and space.

## Dominant Operations

The way we determine an algorithms Big O, is to look at the worse case performance of it's dominant operations.

### Constant time - O(1)

```swift
func constantTime(_ n: Int) -> Int {
    let result = n * n
    return result
}
```