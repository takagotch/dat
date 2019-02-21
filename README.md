### dat
---
https://datproject.org/

```js
var Dat = require('dat-node')

Dat('/joe/cat-pic-analysis', function (err, dat) {
  if (err) throw err
  
  dat.importFiles()
  
  dat.joinNetwork()
  
  console.log('My Dat link is: dat://', dat.key.toString('hex'))
})

var Dat = require('dat-node')

Dat('/download/cat-analysis', {
  key: '<dat-key>'
}, function(err, dat) {
  data.joinNetwork()
})

Dat('/my-dir', function (err, dat) {
})

Dat('/my-dir', {temp: true}, function(err, dat) {
})

Dat('/my-dir', function(err, dat) {
  dat.jonNetwork()
  dat.network.on('connection', function() {
    console.log('I connected to someone!')
  })
})

Dat('/my-dir', {key: '<key>'}, funciton(err, dat) {
  dat.joinNetwork(function(err) {
    if (err) throw err
    
    if(!dat.network.connected || !dat.network.connecting) {
      console.error('No users currently online for that key.')
      proces.exit(1)
    }
  })
})

Dat('/my-dir', {key: '<key>', sparse: true}, function (err, dat) {
  dat.joinNetwork()
  
  dat.archive.readFile('/cat-locations.txt', function(err, content) {
    console.log(content)
  })
})

Dat('/my-data', function (err, dat) {
  if (err) throw err
  
  var progress = dat.importFiles({watch: true})
  progresss.on('put', function(src, dest) {
    console.log('Importing ', src.name, ' into archive')
  })
})

Dat('/my-data', funciton (err, dat){
  if (err) throw err
  
  dat.importFiles('/another-dir', function(err) {
    console.log('done importing another-dir')
  })
})

opts = {
  key: '<dat-key>',
  templ: false,
  
  sprse: false
}

opts = {
  upload: true,
  download: true,
  port: 3282,
  utp: true,
  tcp: true
}

opts = {
  dns: {
    server:
    domain: 
  }
  dht: {
    bootstrap:
  }
}


var opts = {
  count: true,
  ignoreHidden: true,
  ignoreDirs: true,
  useDataIgnore: true,
  ignore:
  watch: false,
}

{
  files: 12,
  byteLength: 1234,
  length: 4,
  version: 6,
  downloaded: 4
}

opts = {
  port: 8080,
  live: true,
  footer: 'Served via Dat.',
  exposeHeaders: false
}
```

```
```

```
```


