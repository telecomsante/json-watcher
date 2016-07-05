# Json watcher

This library purpose is to watch and parse a given json file.

## How to use

```javascript
require('tsante-json-watcher')(jsonFile.path).then(watcher => {
    watcher.on('error', error => console.log('error', error))
    watcher.on('change', json => console.log('json', json))
```
