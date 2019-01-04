# crypto-api-proxy
Build docker image
```
docker build -t crypto-api-proxy .
```

Run docker image
```
docker run -d -p 7676:80 --name crypto-api-proxy crypto-api-proxy
```

That's should be run on localhost port 7676