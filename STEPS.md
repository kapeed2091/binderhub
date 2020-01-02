# Step-0: Checkout to base repo
```
git clone https://github.com/kapeed2091/binderhub.git
cd binderhub
git checkout 23eeb4313d96890e3cc777e614135fa224da868c
```


# Step-1: Build docker file
```
docker build -t kapeed2091/k8s-binderhub:02012020 --file $PWD/helm-chart/images/binderhub/Dockerfile .
docker push kapeed2091/k8s-binderhub:02012020  # push to any registry of your choice
``` 
