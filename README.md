# esm-bug-reproduction

To see the error, clone this repo, note that esm@3.0.49 is specified in package.json, and do the following steps:

```shell
npm install
npm start
```

Then, downgrade to esm@3.0.48 and try again:

```shell
npm uninstall esm
npm install esm@3.0.48
npm start
```

Note that the two results are different!
