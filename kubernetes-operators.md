# Kubernetes Operators
How to build an operator.

## References

### Overview
* Writing Controllers
  * https://github.com/kubernetes/community/blob/master/contributors/devel/controllers.md
* Extend Kubernetes 1.7 with Custom Resources
  * https://thenewstack.io/extend-kubernetes-1-7-custom-resources/
* Extending Kubernetes: Create Controllers for Core and Custom Resources
  * https://medium.com/@trstringer/create-kubernetes-controllers-for-core-and-custom-resources-62fc35ad64a3
* Analyzing value of Operator Framework for Kubernetes community
  * https://itnext.io/analyzing-value-of-operator-framework-for-kubernetes-community-5a65abc259ec
* Kubernetes Deep Dive: Code Generation for CustomResources
  * https://blog.openshift.com/kubernetes-deep-dive-code-generation-customresources/
* A Deep Dive Into Kubernetes Controllers
  * https://engineering.bitnami.com/articles/a-deep-dive-into-kubernetes-controllers.html
* Kubewatch, An Example Of Kubernetes Custom Controller
  * https://engineering.bitnami.com/articles/kubewatch-an-example-of-kubernetes-custom-controller.html
* Steps to generate CRD/Operator code
  * https://github.com/cloud-ark/kubeplus/issues/14
* An Introduction to Extending Kubernetes with CustomResourceDefinitions  
  * https://blog.heptio.com/an-introduction-to-extending-kubernetes-with-customresourcedefinitions-76deb675b27a
* client-go under the hood
  * https://github.com/kubernetes/sample-controller/blob/master/docs/controller-client-go.md#client-go-under-the-hood
  
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
