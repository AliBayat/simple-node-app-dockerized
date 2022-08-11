Build the image:
```
docker build . -t node-app
```

Run the Container:
```
docker run -d --name node-app -p 8080:8080 node-app
```

Visit:
```
http://127.0.0.1:8080
```