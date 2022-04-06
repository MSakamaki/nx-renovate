# renovate nrwl/nx migration config

## usage

`renovate.json`

```json
{
    "extends": ["github>MSakamaki/nx-renovate"]
}
```

`package.json`

```json
{
  "name": "renovate-config-name",
  "version": "0.0.1",
  ...
  "renovate-config": {
    "default": {
      "extends": ["github>MSakamaki/nx-renovate"]
    }
  }
}
```