# Minizip

Minizip framework wrapper for iOS, OSX, tvOS, and watchOS. Based on [nmoinvaz/minizip](https://github.com/nmoinvaz/minizip).

## Installation

### Carthage

[Carthage](https://github.com/carthage/carthage) is the recommended way to install Minizip. Add the following to your Cartfile:

```ruby
github "dexman/Minizip"
```

## Usage

Import Minizip into your Swift code with:

```swift
import Minizip
```

See `Vendor/Minizip/miniunz.c` and `Vendor/Minizip/minizip.c` for examples in C.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## History

### 1.4.0 2018-03-28
- Fixed builds on Xcode 9. Thanks [simonseyer](https://github.com/simonseyer)!

### 1.3.0 2016-11-18
- Use version-less SDK path for MacOSX10.12.sdk compatibility. Thanks [RossAnderson](https://github.com/RossAnderson)!

### 1.2.0 2016-03-29
- Fixes compilation on Xcode 7.3.

### 1.1.0 / 2016-02-07
- Make ioapi_buf and ioapi_mem public.

### 1.0.0 / 2016-02-06
#### Added
- Initial version.
- Exposes Minizip as a framwork to on iOS, OSX, tvOS, and watchOS.
- Fix compiler warnings in minizip under Xcode 7.2.

## Credits

Minizip code taken from [nmoinvaz/minizip](https://github.com/nmoinvaz/minizip).

Original framework module approach by Matt Behrens as documented in [Getting Started Using C Libraries from Swift](https://spin.atomicobject.com/2015/02/23/c-libraries-swift/).

## License

This software may be modified and distributed under the terms of the MIT license. See the LICENSE file for details.
