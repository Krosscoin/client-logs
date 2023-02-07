# Lite library for console logs from clients.

# Install

```sh
npm i @krosschain/client-logs
```

# Usage

```typescript
import { makeConsole, makeOptions } from '@krosschain/client-logs';

const console = makeConsole(makeOptions('verbose'));

console.log('Some arguments');
```

