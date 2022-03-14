### Code gen

```sh
graph codegen
```

### Build

```sh
graph build
```

### Authentication

```sh
graph auth --studio <DEPLOY_KEY>
```

```sh
graph deploy --product hosted-service n4sunday/Subgraphbasic
```

```ts
{
  transferEntities(first: 100) {
    txHash
    id
    from
    to
    value
  }
}
```
