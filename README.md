# personnummer [![Build Status](https://github.com/personnummer/js/workflows/build/badge.svg)](https://github.com/personnummer/js/actions)

Validate Swedish personal identity numbers. Follows version 3 of the [specification](https://github.com/personnummer/meta#package-specification-v3).

Install the module with npm:

```
npm install --save personnummer
```

## Example

```javascript
const Personnummer = require('personnummer');

Personnummer.valid('198507099805')
//=> true
```

See [test.ts](test.ts) for more examples.

## License

MIT
