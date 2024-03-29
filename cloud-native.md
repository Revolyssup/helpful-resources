 # Kubernetes, Docker and other CNCF project related resources and more.
---
[Cgroups, namespaces and Overlayfs](https://www.youtube.com/watch?v=x1npPrzyKfs) - Not for absolute beginners but a good deep dive into the internals of containers.

***
 ##  [Cgroups, namespaces and more](https://www.youtube.com/watch?v=sK5i-N34im8)- A well presented at DockerCon 2015.

![Event image](./assets/cgroup.png)

***
 ##  [Deep dive into docker storage drivers](https://www.youtube.com/watch?v=9oh_M11-foU)- How do those layers you see in images work - Copy on write. 

![Event image](./assets/docker_storage.png)
***
 ##  [Types of docker networking modes](https://www.youtube.com/watch?v=bKFMS5C4CG0)- A good hands-on overview of 7 networking modes in docker. 

![Event image](./assets/docker-net.png)

***
 ##  [Kubernetes Deconstructed- A high level overview](https://vimeo.com/245778144/4d1d597c5e)- Probably one of the best talks on kubernetes.

![Event image](./assets/1.png)

***
##  [A good overview of networking in k8 with examples](https://www.youtube.com/watch?v=0Omvgd7Hg1I)- Knowing the basics of kubernetes is a pre-requisite.

![Event Image](./assets/k82.png)


***

##  [Kubernetes networking and CNI](https://www.youtube.com/playlist?list=PL36qiA-FGdl7n9AKDv1-r18boL9Er57Gk)- Starting from networking basic, he goes through a hands on demo of what CNI does and then how.

![Event Image](./assets/cni.png)
***

##  [Linux namespaces, cgroups and more](https://www.youtube.com/watch?v=x1npPrzyKfs)- If you have a basic knowledge of container technology, this is a deep dive in how it is made possible via cgroups, namespaces and union file systems. And a little about container runtimes and OCI as well.
![Event Image](./assets/container.png)
***

##  [Container networking](https://iximiuz.com/en/posts/container-networking-is-simple/)- Probably, THE BEST article I have read explaining networking in containers.Everything from creating veth pair to establishing successfull communication among network namespaces via bridges. This article is gold. Also this entire [blog](https://iximiuz.com) is gold for anyone interested in cloud native buzzwords.
![Event Image](./assets/container_networking.png)
***

##  [Life of a packet through istio](https://www.youtube.com/watch?v=cB611FtjHcQ)- If you have a good idea of kubernetes, especially how networking in kubernetes work, and also have a little idea of what service meshes are, this video is a great deep dive.

![Event Image](./assets/istio.png)
***

##  [Life of kubernetes watch event](https://www.youtube.com/watch?v=PLSDvFjR9HY)- Watch this before writing custom controllers in kubernetes to understand how the events propogate.

![Event Image](./assets/watch_event.png)
***

##  [Admission Controllers in k8](https://kubernetes.io/blog/2019/03/21/a-guide-to-kubernetes-admission-controllers/)- A good overview blog on how to configure custom webhooks and admssion controllers for incoming CRD's.

![Event Image](./assets/adm.png)
***

##  [Demo of Istio features](https://www.youtube.com/watch?v=7cINRP0BFY8)- A good starter demo of Virtual service/Destination rules/ingress/egress in istio.

![Event Image](./assets/istio-demo.png)



##  [Introduction to Envoy](https://tetrate-academy.thinkific.com/courses/take/envoy-fundamentals/)- A good starter course to understand envoy fundamentals.

![Event Image](./assets/envoy.png)

## [Using eBPF to replace kube-proxy](https://www.youtube.com/watch?v=bIRwSIwNHC0)-  Replacing kube-proxy with BPF programs and IPTABLES with BPF maps. A must watch for anyone interested in Kubernetes networking

![Event Image](./assets/cilium.png)

##  [Lifecycle of a request in Envoy](https://www.envoyproxy.io/docs/envoy/latest/intro/life_of_a_request) - The internals of how a request is processed across both sub-systems in Envoy and a little peak in their code.(basic interface signatures)
 ![Event image](./assets/envoy-proxy.png)

##  [Promql for mere mortals](https://www.youtube.com/watch?v=hTjHuoWxsks) - Cute introduction on promql and its data types
 ![Event image](./assets/promql.png)



## [Containerd by Iximiuz](https://www.youtube.com/watch?v=3_jUWW2j_TI)
