
Here’s a complete first DevOps project for beginners:
Dockerize a Flask app and deploy it on Kubernetes.

1. Create a Simple Flask App
app.py:

requirements.txt:

2. Dockerize the App
Dockerfile:

Build and run locally:

3. Deploy on Kubernetes
deploy.yaml:

Apply the manifest:

4. Access Your App
Visit:
http://<node-ip>:30007
or
http://localhost:30007 (if using minikube with port-forwarding)

5. (Optional) Add a CI/CD Pipeline
Create .github/workflows/docker-deploy.yml:

What you’ll learn:

Python app development
Docker basics
Kubernetes deployment
(Optional) CI/CD automation