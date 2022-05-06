# noisejs-typescript
This is a TypeScript implementation of [`josephg/noisejs`](https://github.com/josephg/noisejs) and wrapped as a class. Simply copy the `perlin.ts` file into your project and you're ready to go.

## How to use
```js
import Perlin from './perlin';

// Seed value is optional, default is 0.
const seed = Math.random();
const noise = new Perlin(seed);

// Call the noise functions to get the noise value for that coordinatre.
noise.simplex2(x, y);
noise.simplex3(x, y, z);

noise.perlin2(x, y);
noise.perlin3(x, y, z);
```
Please read the original repo's README for more information.
