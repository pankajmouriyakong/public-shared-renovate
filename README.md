# public-shared-renovate
Shared Renovate configs available to both public and private repositories 

## Usage

To use the latest add the below line to the top to your `renovate-config.json` file:

```json
{
  "extends": [
    "github>Kong/public-shared-renovate:konnect-frontend-config.json"
  ]
}
```

To use a specific tag add the below line to the top of your `renovate-config.json` file:

```json
{
  "extends": [
    "github>Kong/public-shared-renovate:konnect-frontend-config.json#0.0.1"
  ]
}
```
