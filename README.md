# electron demo 

A very simple barebones app 

#### if you want something a little more advanced checkout -

https://github.com/lansana/ng2-golang-electron

electron app with a golang process

### quick-start tutorial

https://electronjs.org/docs/tutorial/quick-start

### how to package your app

https://www.christianengvall.se/electron-packager-tutorial/

### tldr; install packager 

#### setup 
```
npm install electron-packager --save-dev
npm install electron-packager -g
npm install --save-dev electron-demo
```

#### run packager
```
electron-packager . --overwrite --platform=darwin --arch=x64 --prune=true --out=release-builds

electron-packager . electron-tutorial-app --overwrite --asar=true --platform=win32 --arch=ia32 --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="Electron Demo"

electron-packager . electron-tutorial-app --overwrite --asar=true --platform=linux --arch=x64 --prune=true --out=release-builds
```

### run the packaged app (macos)
```
open -a electron-demo
```
