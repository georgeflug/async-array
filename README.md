# async-array
Syntactic sugar for asynchronous array operations

## Quick Examples

### map
```
// sync
const result1 = [1, 2, 3].map(i => foo(i));

// async
const result2 = await Promise.all(
  [1, 2, 3].map(i => fooAsync(i))
);

// async with async-array library
const result3 = await asyncArray([1, 2, 3])
  .forEach(i => fooAsync(i))
  .await();
```

## Maintainer
### Bumping the version

The patch version is automatically bumped on every commit. To release a major or
minor version, run the interactive command `npm run release`.
