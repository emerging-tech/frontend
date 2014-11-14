# emerging-tech-web

# pubnub api

## streams __from__ the sensor network

### `network_def`

gives the devices connected to the network 

```js
{
  01ef: "0123456789abcdef"
}
```

### `outbound`

gives all readings from the network

```js
{
  node:    "01ef",
  payload: "0007"
}
```

### `node-01ef`

gives the reading from a particular device

```js
"0007"
```

## streams __to__ the sensor network

### `inbound`

sends `0007` to node `01ef`

```js
{
  node:    "01ef",
  payload: "0007"
}
``