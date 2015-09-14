
Simple node wrapper for the audiosear.ch api. 

### Example usage

```javascript
var Audiosearch = require('audiosearch-client-node');

var audiosearch = new Audiosearch(process.env.AUDIOSEARCH_APP_ID, process.env.AUDIOSEARCH_SECRET);

audiosearch.getTastemakers().then(function (tastemakers) {
  // do stuff here
});

audiosearch.searchEpisodes('text query').then(function (results) {
  // do stuff here.
});
```

### Features
- Run queries immediately, no need to wait for authentication
- Promise based
