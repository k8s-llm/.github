# k8s-LLM

k8s-llm is a solution that tries to easily create and maintain a private Open Source AI implementation on Kubernetes.

Whether run on premise or in a Cloud, the idea is that no public AI provider is used, and all context traffic is internal to the k8s cluster.

Then agents, harness, etc that might be running in the cluster or in client side can work as usual.

## Applications

### k8s-model-operator

It is an operator, created using kubebuilder, that allows you to easily create k8s resources to run models.

### k8s-llm-hosting

It is not an actual application, but sets of installation to run models. 

So far it gives some explanations for installing and a set of FluxCD assets to create the installation from stratch (once you are running in a k8s cluster).
