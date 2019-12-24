# Dockerized-ssl-tools
Simple tool for debuging ssl
- [nmap](https://nmap.org/) 
- [testssl.sh](https://github.com/drwetter/testssl.sh)
- [curl](https://curl.haxx.se/)

## Run on docker
```
docker run --rm -ti riskiwah/ssl-tools sh
```
## Run as pod on Kubernetes
```
kubectl apply -f k8s-ssl-tools-pod.yaml
```




