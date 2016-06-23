Netflix Ice on Kubernetes
==========================

This turns on a pod with Doorman in front of it.  Doorman (https://github.com/movableink/doorman) is an oauth proxy with puts authentication in front of this web app that can be exposed through Ingress.

## Oauth Secret
You need to go to Github.com and generate an oauth secret.  The secrets needs to be base64 encoded.

```
echo -n secret-string | base64
```

