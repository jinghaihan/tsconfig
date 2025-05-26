# @octohash/tsconfig

Shared TypeScript configuration presets for different environments.

```sh
pnpm add -D @octohash/tsconfig
```

## Usage

Extend one of the provided configurations in your tsconfig.json based on your project type:

```json
{
  // base | node | web | library
  "extends": "@octohash/tsconfig/web.json"
}
```

## Recommendation

Choose the preset that most closely matches your project environment:

+ `node.json` for backend/Node.js projects

+ `web.json` for frontend/browser projects

+ `library.json` when building shareable libraries

+ `base.json` as a starting point for custom configurations

You can always extend and override specific settings in your project's tsconfig.json as needed.

## License

[MIT](./LICENSE) License © [jinghaihan](https://github.com/jinghaihan)
