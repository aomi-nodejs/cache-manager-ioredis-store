# Redis store for node cache manager

Redis cache store for [node-cache-manager](https://github.com/node-cache-manager/node-cache-manager).

## Installation

```sh
yarn add @aomi/cache-manager-ioredis-store
```

## Usage

```typescript
import { redisStore } from '@aomi/cache-manager-ioredis-store';
import Redis from 'ioredis';

import { redisClient } from './redis';

// use exists redis client
redisStore({
  redis: redisClient,
});
```

## License

Licensed under the [MIT license](./LICENSE).

Fork from [https://github.com/dabroek/node-cache-manager-redis-store](https://github.com/dabroek/node-cache-manager-redis-store)
