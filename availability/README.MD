How to achieve AWS EKS applications availability with lift-and-shifted containerized apps

Blue / Green EKS deployments

### Case
An EKS cluster has a base-line applilcations that are updating with regards to the internal policies. The roll-back is not possible

### Solution
A new EKS cluster with all CRDs need to be created. All necessary components are installed and 