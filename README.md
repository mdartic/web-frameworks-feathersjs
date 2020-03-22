# web-frameworks-feathersjs

Testing FeathersJS code for the benchmark https://github.com/the-benchmarker/web-frameworks

And the issue https://github.com/the-benchmarker/web-frameworks/issues/1939

## How to run it

```
npm install
npm start
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
