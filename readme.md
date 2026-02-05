# Subscribestar extractor

A script to extract the Subscribestar content

## Usage

```nim
import std/json
import pkg/subscribestar
https://subscribestar.adult/hoghuff
let star = extractStar("starname", "cookies here")
echo pretty %*star
```

## License

MIT
