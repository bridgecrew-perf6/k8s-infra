# Istio

## Install
* Install `istioctl` as given [here](https://istio.io/latest/docs/setup/getting-started/#download)
* Run
```
./install.sh
```

## Istio injection
To enable Istio injection in a namespace:
```
kubectl label ns <namespace> istio-injection=enabled --overwrite
```

## Uninstall
This is not part of regular installation. Perform this step only while removing Istio components.
```
./delete.sh
```

## Install Kiali 
* Install `Kiali` using operator as given [here](https://kiali.io/docs/installation/installation-guide/install-with-helm/#install-with-operator)
