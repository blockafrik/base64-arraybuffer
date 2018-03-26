# base64-arraybuffer
>Javascript module for converting base-64 to arraybuffer and from arraybuffer to base-64



## Install

```
$ npm install base64-arraybuffer
```


## Usage

```js
var base64_arraybuffe r= require('base64-arraybuffer');

####Converting  ArrayBuffer to base_64

var uint8 = new Uint8Array ([ 73, 32, 108, 111, 118, 101, 32, 65, 102, 114, 105, 99, 97 ])
var base64_value = base64_arraybuffer.ab_2_base64(uint8)
//=> SSBsb3ZlIEFmcmljYQ==


####Converting Base_64 to Arraybuffer

arrayBuffer = base64_arraybuffer.base64_2_ab(base64_value)
//=> Uint8Array [ 73, 32, 108, 111, 118, 101, 32, 65, 102, 114, 105, 99, 97 ]
```


## Related

## License

MIT © [Andrews Agyemang Opoku](http://fandrews.com)
