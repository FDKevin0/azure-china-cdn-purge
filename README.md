# Azure China CDN Purge

This Action could Purge CDN Cache for Azure China

[Offcial Document](https://docs.azure.cn/zh-cn/cdn/cdn-api-add-purge)

## Inputs

## `subscriptionId`

**Required** The subscription ID.

## `endpointId`

**Required** The endpoint ID.

## `path`

**Required** Purge path.

## `keyId`

**Required** API key ID.

## `keyValue`

**Required** API key value.

## Example usage

```yml
uses: fdkevin0/azure-china-cdn-purge@v1
with:
  subscriptionId: xxxxxxxxx
  endpointId: xxxxxxxxx
  path: xxxxxxxxx
  keyId: xxxxxxxxx
  keyValue: xxxxxxxxx
```
