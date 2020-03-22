# web-frameworks-feathersjs

Testing code for the three routes for web framework benchmark

Related to the repo https://github.com/the-benchmarker/web-frameworks/

And the issue https://github.com/the-benchmarker/web-frameworks/issues/1764

## How to run it

```
npm install
node app.js
```

## How to test it

```
curl http://localhost:3000/
```

Return a HTTP 200, empty.

```
curl http://localhost:3000/user/123
```

Return a HTTP 200, with 123 in body.

```
curl -X POST http://localhost:3000/user
```

Return a HTTP 200, empty.