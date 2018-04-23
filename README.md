# IPFS Demonstration

1) Init node project 
> npm init

2) install ipfs-js
> npm install --save ipfs-js

3) in index.js
use 
> var ipfs = require('ipfs-js');

4) follow command to build min.js
> browserify index.js --standalone ipfs > lib/ipfs.min.js

5) and you have to include in index.html like,
in head tag
<script src="./lib/ipfs.min.js"></script>
and in body tag
<script>
console.log("IPFS Object",ipfs);
</script>
