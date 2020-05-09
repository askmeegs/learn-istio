# ⛵️ Learn Istio!

An [Istio](https://istio.io) + service mesh resource list.

![](https://pbs.twimg.com/media/DlNQYQ9WsAEHc-n?format=jpg&name=medium)

[source](https://twitter.com/deniseyu21/status/1032258052114841600/photo/1) - Denise Yu


## 🥳 Introduction

- [How Istio works (IBM)](https://www.ibm.com/cloud/learn/istio)
- [Blog Post - Service Mesh Pattern, by Phil Calcado](https://philcalcado.com/2017/08/03/pattern_service_mesh.html)
- [ebook - Istio Explained - Getting Started with Service Mesh - Lin Sun and Daniel Berg, IBM](https://www.ibm.com/account/reg/us-en/signup?formid=urx-42654)
- [ebook - The Service Mesh Era (Google Cloud)](https://services.google.com/fh/files/misc/the_service_mesh_era_architecting_securing_and_managing_microservices_with_istio_white_paper.pdf)
- [Istio docs - what is Istio? ](https://istio.io/docs/concepts/what-is-istio/ ) (in depth)
- [Istio docs - Getting Started](https://istio.io/docs/setup/getting-started/)
- [Video - Incrementally Adopting Istio - Sandeep Parikh](https://www.youtube.com/watch?v=0cgTHQFXYPQ)
- [Slides - Service Mesh from the Ground Up (O'Reilly Software Architecture Conference - 2020)](http://bit.ly/istio-sacon)


## 📊 Observability

- [Istio Docs - Observability concepts](https://istio.io/docs/concepts/observability/)
- [Task - Using Istio's Grafana Dashboards](https://istio.io/docs/tasks/telemetry/metrics/using-istio-dashboard/)
- [Task - Service Graph with Kiali ](https://istio.io/docs/tasks/telemetry/kiali/)
- [Sample - Using Google Cloud Monitoring (Stackdriver) for Istio metrics ](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/istio-stackdriver)


## 🔒 Security

- [Istio docs - Security ](https://istio.io/docs/concepts/security/)
- [Sample - Introduction to Istio Security ](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/security-intro)
- [Istio by Example - Mutual TLS](istiobyexample.dev/mtls)
- [Istio by Example - JWT Authentication](istiobyexample.dev/jwt)
- [Istio By Example - Authorization](https://istiobyexample.dev/authorization/)


## 🚦 Traffic Management

- [Sample - Canary Deployments with Istio](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/istio-canary-gke)
- [Istio docs - Virtual Services and DestinationRules ](https://istio.io/docs/concepts/traffic-management/#rule-configuration)
- [Istio docs - task - Istio Ingress Traffic (Gateway)  ](https://istio.io/docs/tasks/traffic-management/ingress/)
- [Istio docs - task - Istio Egress Traffic](https://istio.io/docs/tasks/traffic-management/egress/) (ServiceEntry)
- [Blog Post - Traffic Shadowing with Istio: Reducing the Risk of Code Release - Christian Posta](https://blog.christianposta.com/microservices/traffic-shadowing-with-istio-reduce-the-risk-of-code-release/)
- [Istio by example - path-based routing](https://istiobyexample.dev/path-based-routing/)
- [Istio by example - modify HTTP response headers](https://istiobyexample.dev/response-headers/)
- [Istio by example - multiple traffic rules per service](https://istiobyexample.dev/multiple-traffic-rules/)
- [Istio docs - Circuit Breaking](https://istio.io/docs/tasks/traffic-management/circuit-breaking/)
- [Video- Istio in production - Day 2 traffic routing](https://www.youtube.com/watch?v=7cINRP0BFY8)

## 🌏 Multicluster

- [Docs - Istio Deployment Models](https://istio.io/docs/ops/deployment/deployment-models/)
- [Sample - Multicluster with replicated control planes](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/multicluster-gke/dual-control-plane)
- [Sample - Multicluster with a shared control plane ](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/multicluster-gke/single-control-plane)


## ⬆️ Virtual Machines

- [Istio samples - integrating a Google Compute Engine VM into a GKE-based Istio mesh](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/mesh-expansion-gce)
- [Istio samples - VM to GKE migration with Multicluster Istio](https://github.com/GoogleCloudPlatform/istio-samples/tree/master/multicluster-gke/vm-migration)
- [Video- Life outside the Cluster - Adding a Virtual Machine to an Envoy Service Mesh - Kubecon '19 (Ameer Abbas, Megan O'Keefe)](https://www.youtube.com/watch?v=0B8maYcjq_c)

## 📦 Extensibility

- [Istio Docs - Extensibility](https://istio.io/docs/concepts/wasm/)
- [Istio Blog - Redefining Extensibility in Proxies - introducing WebAssembly to Envoy and Istio](https://istio.io/blog/2020/wasm-announce/) (2020)
- [WebAssembly Hub](https://webassemblyhub.io/)


## 🔎 Troubleshooting

- [Istio Docs - Common Problems](https://istio.io/docs/ops/common-problems/)
- [Diagnose Your Configuration with `istioctl analyze`](https://istio.io/docs/ops/diagnostic-tools/istioctl-analyze/)
- [Understanding Envoy Proxy HTTP Access Logs - Richard Li, Ambassador Blog](https://blog.getambassador.io/understanding-envoy-proxy-and-ambassador-http-access-logs-fee7802a2ec5)

## 🌊 Deep Dives

- [Video- Life of a packet through Istio - Matt Turner ](https://www.youtube.com/watch?v=cB611FtjHcQ)
- [Kubernetes Podcast - Istio, with Jasmin Jaksic and Dan Ciruli](https://kubernetespodcast.com/episode/015-istio/) (2018)
- [Kubernetes Podcast - Istio 1.2, with Louis Ryan](https://kubernetespodcast.com/episode/058-istio-1.2/) (2019)
- [Kubernetes Podcast - Invention, IBM and Istio, with Lin Sun](https://kubernetespodcast.com/episode/086-invention-ibm-istio/) (2020)
- [ebook - Introducing Istio Service Mesh for Microservices - Burr Sutter and Christian Posta](https://developers.redhat.com/books/introducing-istio-service-mesh-microservices/) (2019)