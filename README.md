
### Example usage

```
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
- Will run queries after you're authenticated, no need to wait
- Promise based
