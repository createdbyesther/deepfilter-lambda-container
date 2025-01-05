# DeepFilter Lambda Container

This project implements a Lambda function using a container image to enhance audio files using the DeepFilter model.

# Build the Image
```
docker build -t dfl_img .
```

# Build the Container
```
docker run -p 9000:8080 --name dfl-container dfl_img
```