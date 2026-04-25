# Build
docker build -t <dockerhub-username>/flask-app:latest .

# Test locally → visit http://localhost:5000
docker run -d -p 5000:5000 <dockerhub-username>/flask-app:latest

# Login and push
docker login
docker push <dockerhub-username>/flask-app:latest