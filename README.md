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

### Deploy Graph Node

```sh
graph create n4sunday/Subgraphbasic --node http://localhost:8020
# graph deploy --ipfs http://localhost:5001 --node http://localhost:8020 n4sunday/Subgraphbasic ./subgraph.yaml
graph deploy --ipfs http://localhost:5001 --node http://localhost:8020 n4sunday/Subgraphbasic
```
