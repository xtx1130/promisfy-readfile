# promisfy-readfile

> promisfy for readfile


```bash
npm install promisfy-readfile
```
## useage

```js
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


## License

MIT
