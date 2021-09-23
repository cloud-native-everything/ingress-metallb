# Ingress and Metallb

MetalLB is a young project of a load-balancer implementation for bare metal Kubernetes clusters, using standard routing protocols. Ingress exposes HTTP and HTTPS routes from outside the cluster to services within the cluster. Traffic routing is controlled by rules defined on the Ingress resource.

We'll show some configurations examples of how to use ingress controller and a load-balancer service built with metallb. In this case, I am using NGNIX ingress controller.

If you want to see how this service was implemented, read my previous post: [Calico and MetalLB working together with BGP] (https://www.cloud-native-everything.com/calico-and-metallb-working-together-with-bgp/)

Check step-by-step details in my post: Ingress and Metallb (https://www.cloud-native-everything.com/ingress-and-metallb)
