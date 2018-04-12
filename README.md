## ava babel options

#### Get Start

```bash
$ yarn install
$ yarn test
```

#### Issue

- `babelrc: false` not working at all. 
- If you remove `.babelrc` file and excute `yarn test`, it will yell at you about **SyntaxError**, which means the `babel` config under `ava` not working.
