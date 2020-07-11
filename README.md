# ElectronExample


## NPM Commands

#### Install normal Dependencies and devDependencies
```bash
npm run install-all 
```

#### Rebuild for electron
if you have an Package that must rebuild for electron you must edit the package.json

```text
Replace in package.json File <PACKAGE> with your Package
```

```javascript
"rebuild": "electron-rebuild -f -w <PACKAGE>"
```

```bash
npm run rebuild
```


#### Run App in Development 
```bash
npm run app
```

#### Package your App for your OS on your OS
```bash
npm run package-mac 
npm run package-win 
npm run package-linux
```


