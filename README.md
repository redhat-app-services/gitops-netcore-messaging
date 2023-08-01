## .NET Core API Serverless with 3Scale, Service Mesh and Postgres database

Demo description and tools used TBD.


### Provisioning
Clone this or use the raw files url if preferred, then assuming a fresh install of OpenShift run the first command to install the Red Hat GitOps operator:

```
oc create -k gitops/manifests/operators/openshift-gitops-operator/overlays/latest
```

Once the operator is installed, we use the App of Apps pattern to initiate the install of all other operators. Notice this might take a while to finish the sync and install everything.

```
oc create -k gitops/manifests/cluster/bootstrap/base
```

### Idea and execution

Demo workflow description TBD.