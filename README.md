# MessagePack

A [MessagePack](https://msgpack.org/) encoder and decoder for `Codable` types.

This functionality is discussed in Chapter 7 of
[Flight School Guide to Swift Codable](https://gumroad.com/l/codable).

## MessagePackEncoder

```swift
let encoder = MessagePackEncoder()
let value = try! encoder.encode(["a": 1, "b": 2, "c": 3])
// [0x83, 0xA1, 0x62, 0x02, 0xA1, 0x61, 0x01, 0xA1, 0x63, 0x03]
```

## MessagePackDecoder

_(Implementation coming soon!)_

## License

MIT

## Contact

Mattt ([@mattt](https://twitter.com/mattt))
