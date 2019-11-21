##### Steps:

Build the app.
```mvn clean package```

Build the image.
```docker build -t spring-boot-docker-test .```

Run the image.
```docker run -p 5000:8080 spring-boot-docker-test```

check if the app is working.
```curl http://localhost:5000```
