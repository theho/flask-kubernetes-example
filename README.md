# Flask Example for Docker and Kubernetes

## Work-In-Progress

## To Build

```
git clone git@github.com:theho/flask-kubernetes-example.git
cd flask-kubernetes-example

docker build . -t flask-kubernetes-example

docker run -d -p 5000:5000 flask-kubernetes-example

curl http://localhost:5000

```