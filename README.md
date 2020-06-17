[![CircleCI](https://circleci.com/gh/aws/aws-app-mesh-controller-for-k8s/tree/master.svg?style=svg)](https://circleci.com/gh/aws/aws-app-mesh-controller-for-k8s/tree/master)
[![Go Report Card](https://goreportcard.com/badge/github.com/aws/aws-app-mesh-controller-for-k8s)](https://goreportcard.com/report/github.com/aws/aws-app-mesh-controller-for-k8s) 

## Note: This [master branch](https://github.com/aws/aws-app-mesh-controller-for-k8s/tree/master) is for our new release candidate of [appmesh-controller](https://github.com/aws/eks-charts/tree/master/stable/appmesh-controller). Please refer to [legacy-controller branch](https://github.com/aws/aws-app-mesh-controller-for-k8s/tree/legacy-controller) for old versions.


<p>
    <img src="docs/assets/images/aws_appmesh_icon.svg" alt="App Mesh Logo" width="200" />
</p>

## AWS App Mesh Controller For K8s

AWS App Mesh Controller For K8s is a controller to help manage [App Mesh](https://aws.amazon.com/app-mesh/) resources for a Kubernetes cluster.  The controller watches custom resources for changes and reflects those changes into the [App Mesh API](https://docs.aws.amazon.com/app-mesh/latest/APIReference/Welcome.html). It is accompanied by the deployment of three custom resource definitions ([CRDs](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)): meshes, virtualnodes, virtualservices, virtualgateways and gatewayroutes.  These map to App Mesh API objects which the controller manages for you.

## Documentation
Checkout our [Live Docs](https://aws.github.io/aws-app-mesh-controller-for-k8s/)!