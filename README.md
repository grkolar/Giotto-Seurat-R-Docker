# Giotto-Seurat-R-Docker
Custom Dockerfile with Giotto and Seurat

This is a custom docker image adding Seurat and a few other useful tools for the Yosten-Kolar lab specifically.

It is based on this very solid docker image:

https://hub.docker.com/r/delron01/giotto
For the latter to launch it is 

docker pull delron01/giotto:latest

docker run --rm -p 8787:8787 -e PASSWORD=mypassword delron01/giotto:latest
