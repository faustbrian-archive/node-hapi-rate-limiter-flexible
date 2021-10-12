**You can help the author become a full-time open-source maintainer by [sponsoring him on GitHub](https://github.com/sponsors/faustbrian).**

---

# @faustbrian/node-hapi-rate-limiter-flexible

[![npm version](https://badgen.net/npm/v/@faustbrian/node-hapi-rate-limiter-flexible)](https://npm.im/@faustbrian/node-hapi-rate-limiter-flexible)

## Installation

```
pnpm install @faustbrian/node-hapi-rate-limiter-flexible
```

## Usage

```ts
import { plugin } from "@faustbrian/node-hapi-rate-limiter-flexible";

await server.register({
	plugin,
	options: {
    // https://github.com/faustbrian/node-hapi-rate-limiter-flexible/blob/main/source/index.ts#L17-L23
  },
});
```

## License

This is an open-sourced software licensed under the [AGPL-3.0-or-later](LICENSE).
