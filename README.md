# Link
[comparing-service-meshes-linkerd-vs-istio](https://glasnostic.com/blog/comparing-service-meshes-linkerd-vs-istio)

# Istio

What is Istio?

Istio is an open source service mesh initially developed by Google, IBM and Lyft. The project was announced in May 2017, with its 1.0 version released in July 2018. [istio is built on top of the Envoy proxy](https://glasnostic.com/blog/microservices-architecture-patterns-service-mesh-glossary#Envoy) which acts as its data plane. Although it is quite clearly the most popular service mesh available today, it is for all practical purposes only usable with Kubernetes.

# [What is Linkerd?](https://glasnostic.com/blog/comparing-service-meshes-linkerd-vs-istio)

Linkerd (rhymes with “chickadee”) is the original service mesh created by Buoyant, which coined the term in 2016. It is the official service mesh project supported by the Cloud-Native Computing Foundation, Like Twitter’s Finagle, on which it was based, Linkerd was originally written in Scala and designed to be deployed on a per-host basis.

Criticisms of its comparatively large memory footprint subsequently led to the development of Conduit, a lightweight service mesh specifically for Kubernetes, written in Rust and Go.

The Conduit project has since been folded into Linkerd, which relaunched as Linkerd 2.0 in July of 2018.

While Linkerd 2.x is currently specific to Kubernetes, Linkerd 1.x can be deployed on a per-node basis, thus making it a more flexible choice where a variety of environments need to be supported.
