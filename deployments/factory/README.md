# Deploy with 2SV Factory

All of the previously deployments, `docker`, `kubernetes` and `openshift` are great for a technical audience. However for business users, it might be more convenient to have a clean web ui, that one can leverage to add one or more cameras (2SV Agents), without the hassle of the technical resources.

That's exactly why we have build [2SV Factory](https://github.com/2SV/factory). It's a web ui on top of a Kubernetes cluster, which allows a non-technical users to administer and configure a video landscape.

![Factory login](./factory-login.gif)

The idea of [2SV Factory](https://github.com/2SV/factory) is that one can configure and deploy a camera, by filling-in some basic input fields. Once done [2SV Factory](https://github.com/2SV/factory), will create the relevant resources in your Kubernetes cluster.
