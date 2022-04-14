# vet-service
Python Django REST API service for CRUD operations on Vet

# Pre-requisites
- Git 
- Docker

# Run the service

Checkout locally the code from repo
`git clone https://github.com/paulcleetus/petclinic.git`

Build the Docker Image
`docker build -t vet-service .`

Run the Docker Image, expose the containers 8030 port to the local machines 8030 port
`docker run -it -p 8030:8030 vet-service`
