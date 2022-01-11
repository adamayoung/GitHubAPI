# GitHubAPI

![CI](https://github.com/adamayoung/GitHubAPI/workflows/CI/badge.svg)

A Swift Package for the GitHub API <https://docs.github.com/en/rest>

## Requirements

* Swift 5.5+

## Installation

### [Swift Package Manager](https://github.com/apple/swift-package-manager)

Add the GitHubAPI package as a dependency to your `Package.swift` file, and add it as a dependency to your target.

```swift
// swift-tools-version:5.5

import PackageDescription

let package = Package(
  name: "MyPackage",
  dependencies: [
    .package(url: "GitHubAPI", upToNextMajor: "1.0.0")
  ],
  targets: [
    .target(name: "MyProject", dependencies: ["GitHubAPI"])
  ]
)
```

## References

* [https://docs.github.com/en/rest](https://docs.github.com/en/rest)
