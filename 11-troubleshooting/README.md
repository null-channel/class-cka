Chalange 1:

Using the base kind file deploy a cluster `kind create cluster --config=../base-kind-config.yaml`
create the "important" deployment
Check how many containers are in the pod (should be 2)
attach a busybox container too the pod that is already started.
How many containers are now in the pod (should be 3)


Chalange 2:
Create a static pod on the control plane node (need to look into this to see if it can be done in kind, I think it can be)
