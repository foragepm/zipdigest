# zipdigest

Generate digests and manifests of go module zip contents.

## Installation

```
npm install zipdigest
```

## Usage

```javascript
const {zipDigest, zipManifest} = require('zipdigest');

// generate the digest of the contents of a go module zip file
var digest = await zipDigest(pathToZip)

// generate the manifest of the contents of a go module zip file
var metafile = await zipManifest(pathToZip);
```

## Development

Forest needs your help!  There are a few things you can do right now to help out:

Read the [Development documentation](https://github.com/forestpm/forest/docs/development.md), [Code of Conduct](https://github.com/forestpm/forest/docs/code-of-conduct.md) and [Contributing Guidelines](https://github.com/forestpm/forest/docs/contributing.md).

- **Check out existing issues** The [issue list](https://github.com/forestpm/zipdigest/issues) has many that are marked as ['help wanted'](https://github.com/forestpm/zipdigest/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22help+wanted%22) which make great starting points for development, many of which can be tackled with no prior IPFS knowledge
- **Perform code reviews** More eyes will help
  a. speed the project along
  b. ensure quality, and
  c. reduce possible future bugs.
- **Add tests**. There can never be enough tests.

## Copyright

[MIT License](LICENSE) © 2021 [Andrew Nesbitt](https://github.com/andrew).
