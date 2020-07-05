## FAQ

This Frequently Asked Question document is meant to help people for the most common things.

### How to hide errors ?

Use `hideErrors: true` in createClient options
You may also choose to add these listeners :
```js
client.on('error', () => {})
client.on('end', () => {})
```

### How can I make a proxy with this ?

* See this example https://github.com/PrismarineJS/node-minecraft-protocol/tree/master/examples/proxy
* Read this issue https://github.com/PrismarineJS/node-minecraft-protocol/issues/712
* Check out this app https://github.com/wvffle/minecraft-packet-debugger