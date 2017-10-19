# Canvas API
> Access the Canvas LMS api easily using Canvas Api

## Usage
```js
var Canvas = require('canvas-wrapper')
var canvas = new Canvas({
    url: 'https://<canvas-url>/api/v1',
    token: '<YOUR-DEV-TOKEN>'
})
```

**GET**
```js
canvas.get('accounts/1') // any url
  .then(data => {
      console.log(data);
  })
  .catch(err => {
      throw err;
  })
```
