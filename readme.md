# promisfy-readfile

> simple promisfy for readfile


```bash
npm install promisfy-readfile
```
## useage

```js
'use strict';

const readFile = require('promisfy-readfile');
let genera = async ()=>{
	let da = await readFile(file);
	return da;
};

genera().then(res=>{
	console.log(res)//buffer type
}).catch(err=>{
	throw err
});
```

##issues
If you have any question,please click [issues](https://github.com/xtx1130/promisfy-readfile/issues)

## License

MIT
