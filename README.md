# Helm3
This repository contains packaged Helm charts provided by C.SCOTTI for training

# Add Repository (stable)
```
helm repo add cscotti-stable https://cscotti.github.io/Helm3/stable
helm repo update
```
# Install package
```
helm install rundeck cscotti-stable/rundeck [--version=0.3.6]
```
