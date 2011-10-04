# Planet Riak 

This is the repo for Planet Riak. 

# Dependencies

* [Node.js](http://nodejs.org/#download)
* [Express](http://expressjs.com/) 

# Making it run 

1. Modify the port number (currently defaults to 4000) and build path in `config.js` located in the top level directory. 
2. Run 

```bash
node server.js
```

from the top level directory. 

3. Head on over to http://localhost:$PORT_NUMBER to see your creation. 

# To Make It Pretty

You'll want to mess with `templates/index.mustache` and `nodeplanet/site.css`. 

# To Add Your Site 

Add your info under `nodeplanet/config.json` and send us a pull request. 

# Thanks 

To Mikeal Rogers for releasing [the code for Planet Node](https://github.com/mikeal/node). 
