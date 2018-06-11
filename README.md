# basic-swift

A handy reference for basic Swift language concepts.
https://swift.org/documentation/ but with my own examples so
that I can practice using the documentation and remember the concepts better.

* https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html
* https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html
* https://docs.swift.org/swift-book/LanguageGuide/Enumerations.html

## Basic Types

* String
* Int // Whole numbers with no fractional component
* Double // Has a precision of at least 15 decimal digits
* Float // Can have a precision as little as 6 decimal digits
* Bool

## Constants and Variables

```swift
let exampleConstant = 0 // Constant
var exampleVariable = 0 /* Variable */
```

## Tuples

let http404Error = (404, "Not Found")

## Optionals

```swift
let testString = "hello"
let optionalResult = Int(testString)
testString = "123"
optionalResult = Int(testString)
```

## Basic operators

* `==` is the equal to operator
* `!=` is the not equal to operator

## Whether an optional contains a value

```swift
if example != nil {
    print("example contains a value")
}
```

## Arrays



## Sets

A set stores distinct values of the same type in a collection with no defined ordering.

You can use a set instead of an array when:
1. the order of items is not important
2. or when you need to ensure that an item only appears once.
