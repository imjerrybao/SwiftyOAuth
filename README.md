# SwiftyOAuth

```swift
let github: Provider = .GitHub(id: "client-id", secret: "client-secret")

github.authorize { result in
    if let credentials = result.credentials {
        print(credentials.token)
    }
}
```

## Usage

### Providers

- GitHub
- Twitter
- Facebook
- Weibo
- Instagram
- Dribbble

## Demo

## Installation

#### Carthage

#### CocoaPods

## License