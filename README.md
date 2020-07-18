INSTALL TOOLS

Version as default
```
TERRAFORM_VERSION="0.12.28"
HELM_VERSION="v3.2.4"
KUBECTL_VERSION="v1.17.3"
ANSIBLE_VERSION="2.9.10"
```

```bash
make terraform TERRAFORM_VERSION="X.Y.Z"
make helm HELM_VERSION="vX.Y.Z"
make kubectl KUBECTL_VERSION="vX.Y.Z"
make ansible ANSIBLE_VERSION="2.9.10"
```

<!-- START makefile-doc -->
```
$ make help 
Klaatu Barata Nitko!
all                            Install Profile, IaC, Cloud and terminal addons 
```
<!-- END makefile-doc -->
