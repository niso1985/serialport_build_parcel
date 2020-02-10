```@bash
yarn add serialport
parcel start
```
then occur foloowing error
```
Uncaught TypeError: exists is not a function
    at Function.getRoot (index.js:1790)
    at bindings (index.js:1790)
    at Object.parcelRequire.node_modules/@serialport/bindings/lib/linux.js.util (index.js:1790)
    at newRequire (util.js:43)
    at localRequire (poller.js:26)
    at Object.parcelRequire.node_modules/@serialport/bindings/lib/index.js.debug (index.js:1790)
    at newRequire (util.js:43)
    at localRequire (poller.js:26)
    at Object.parcelRequire.node_modules/serialport/lib/index.js.@serialport/stream (index.js:1790)
    at newRequire (util.js:43)
```
