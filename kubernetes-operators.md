# Kubernetes Operators
How to build an operator.

## References

### Overview
* Analyzing value of Operator Framework for Kubernetes community
  * https://itnext.io/analyzing-value-of-operator-framework-for-kubernetes-community-5a65abc259ec
* Kubernetes Deep Dive: Code Generation for CustomResources
  * https://blog.openshift.com/kubernetes-deep-dive-code-generation-customresources/

### Examples
* Simple controller for watching Foo resources as defined with a CustomResourceDefinition (CRD).
  * https://github.com/kubernetes/sample-controller
* Manages NATS clusters atop Kubernetes, automating their creation and administration.
  * https://github.com/nats-io/nats-operator
* Creates/configures/manages Prometheus clusters atop Kubernetes
  * https://github.com/coreos/prometheus-operator
* Lostrómos is a service that creates Kubernetes resources based on a Custom Resource endpoint in the Kubernetes API
  * https://github.com/wpengine/lostromos

### Tools
* Golang code-generators used to implement Kubernetes-style API types.
  * https://github.com/kubernetes/code-generator
* SDK for building Kubernetes applications. Provides high level APIs, useful abstractions, and project scaffolding.
  * https://github.com/operator-framework/operator-sdk
