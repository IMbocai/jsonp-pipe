# jsonp-pipe
an implement of jsonp.

# usage

```
npm install jsonp-pipe
```

```
<script type="text/javascript" src="jsonp-pipe/index.js"></script>
```

or

```
import jsonpPipe from 'jsonp-pipe'
```

# example

```
jsonpPipe({
    url:url,
    callback:"callback",//可选
    data:{}, //可选
    success:function(resp){
    },
    fail:function(err){
    },
    time:time,//可选
    cache:true//可选
})
```
