# sitkmutt-bookinfo-reviews


# Update Dockerfile Version
- Gradle: gradle:7.2.0-jdk11
- Websphere: websphere-liberty:21.0.0.9-kernel-java8-ibmjava


# Bookinfo Reviews Service
Reviews service has been developed on Java

## How to run 

```bash
# Build Docker Image for reviews service
docker build -t reviews .

# Run reviews service on port 8082
docker run -d --name reviews -p 8082:9080 reviews
```
* Test `/reviews/{id}` and `/health`


