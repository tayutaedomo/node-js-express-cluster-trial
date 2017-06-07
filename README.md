# node-js-express-cluster-trial
Try express-cluster

See also below links
- https://devcenter.heroku.com/articles/node-concurrency
- https://www.npmjs.com/package/express-cluster

# Setup on your local
Install node-dev if you need.
```
$ npm install -g node-dev
```

Set environment variables.
```
export WEB_CONCURRENCY=<Concurrency count>
```

git clone and start app.
```
$ git clone git@github.com:tayutaedomo/node-js-express-cluster-trial.git
$ npm install
$ node app.js
```
Your app should now be running on http://localhost:3000.

