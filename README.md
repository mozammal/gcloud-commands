# gcloud-commands

# get cluster lists

gcloud container clusters list

# fetching cluster end point and auth data for kubernetese cluster

gcloud container clusters get-credentials my-cluster  --zone us-central1-a --project ultimate-hydra-288114

# create kubernetese cluster on gcloud

gcloud container clusters create my-cluster --issue-client-certificate --enable-basic-auth

# get all nodes in the cluster

kubectl get nodes

# get detaisl of an object resource

kubectl get nodes/gke-my-cluster-default-pool-b5fc7f09-pg2s -o json

# delete an object 
kubectl delete  nodes/gke-my-cluster-default-pool-b5fc7f09-pg2s
## launch a pod
kubectl run <NAME> --image=<URI> 
  


