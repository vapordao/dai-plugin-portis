# dai-plugin-portis

A [Vai.js][vaijs] plugin for using [portis](portis.io/) in a browser environment.

## Example usage

This plugin is not yet published to npm. So use [link](https://www.npmjs.com/package/link) to use it in oasis app.

```js
import portisPlugin from '@makerdao/dai-plugin-portis';
import Maker from '@makerdao/dai';

const maker = await Maker.create('http', {
  plugins: [portisPlugin],
});

// this will not resolve until the account is set up
await maker.authenticate();

```

[vaijs]: https://github.com/vistadao/vai.js
