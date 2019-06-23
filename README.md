> # WIP
> ## The package is still in development stage



<p align="center" >
    <img src="https://imgur.com/A2YgC4S.png" width="400px" />
</p>
<h1  align="center"> webpack-plugin-bundlesize 📦 </h1>

<p align="center" >
Show with plugin or loader is being run currently in CLI
</p>




## Usage
1. **Installation**
```bash
$ npm i webpack-plugin-bundlesize
```

2. In your webpack config
**webpack.config.js** (Your webpack config file)
```js
const webpackBundleSize = require("webpack-plugin-bundlesize")

...
    plugins: [
        new webpackBundleSize(options),
        ...
    ],

...  // rest of your configuration

```

3. `Options` - Optional
```js
{
    sizeLimit : your-size-in-KB // Default is 3
}
```



## TODO
- [ ] To implement the current in watchRun hook

- [ ] To recommend some optimizations when size exceeding

- [ ] To implement the logo and make the looks better

- [ ] To suggest optmizations
   - [ ] read the config and check whether the splitchunk is implemented or not
   - [ ] Minify plugin
   - [ ] Codespliting suggestion

- [ ] Typescript Migration
