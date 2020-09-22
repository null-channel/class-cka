
Chalange:
Usinging the base kind config create a cluster
Using kubectl apply the busy-node-solector.yaml  busy-pod-affinity.yaml files found in this directory
Get all pods to run on worker 3
Using kubectl apply the last yaml file and ensure it runs on any node but worker 3

Links:
https://kubernetes.io/blog/2017/03/advanced-scheduling-in-kubernetes/
https://kubernetes.io/docs/concepts/configuration/pod-priority-preemption/
https://kubernetes.io/docs/concepts/policy/resource-quotas/#limit-priority-class-consumption-by-default
https://kubernetes.io/docs/concepts/configuration/pod-priority-preemption/#priorityclass
https://kubernetes.io/docs/reference/scheduling/policies/
https://kubernetes.io/docs/concepts/scheduling-eviction/kube-scheduler/
https://godoc.org/github.com/nextgearcapital/kubernetes/plugin/pkg/scheduler/algorithm/priorities

