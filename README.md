# Useful scripts
Some useful scripts

## Remove pushed file from git
```
git rm -r --cached .
git add .
git commit -m "Removed ignored files."
```

## Kubernetes Deployment Image
The Pods don't start?
Check [this](https://iximiuz.com/en/posts/kubernetes-kind-load-docker-image/) out, maybe that is the solution.
