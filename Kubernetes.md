# Kubernetes?

Kubernetes is an open-source container orchestration system which is used to automate the management, scaling, and deployment of software. Kubernetes was first created by *Google*, but the *Cloud Native Computing Foundation* now looks after the project.

Kubernetes streamlines application management by automating operational activities associated with container management and providing built-in commands for application deployment, rollout of updates, scaling up and down to accommodate changing requirements, monitoring, and more.

## What can you do with Kubernetes?

The primary benefit of implementing Kubernetes in your environment, particularly if you are optimising app development for the cloud, is that it provides a platform for scheduling and running containers on clusters of physical or virtual machines (VMs).

In general, it enables you to fully implement and rely on container-based infrastructure in production environments. And, because Kubernetes is all about automating operational tasks, you can do many of the same things for your containers that other application platforms or management systems allow.

Developers can also use Kubernetes patterns to construct cloud-native apps using Kubernetes as a runtime platform. Patterns are the tools that a Kubernetes developer needs to create container-based apps and services.

using Kubernetes allows you to do the following:

* Containers can be orchestrated over several hosts.
* Improve your hardware utilisation to maximise the resources required to run your enterprise apps.
* Control and automate the deployment and updating of applications.
* To execute stateful apps, mount and add storage.
* On-the-fly scaling of containerized apps and their resources.
* Declaratively manage services to ensure that deployed applications always perform the way you intended them to.
* With autoplacement, autorestart, autoreplication, and autoscaling, you can self-diagnose and self-heal your apps.

## Basic terminologies in Kubernetes.

1. **Control Plane**: The set of processes that manage Kubernetes nodes. This is the source of all task assignments. It is the hub of our Kubernetes cluster. Along with information on the cluster's state and configuration, we can discover the Kubernetes components that manage the cluster in this location. The crucial task of ensuring that your containers are running in adequate numbers and with the required resources is handled by these fundamental Kubernetes components.

   Your computing devices are always in communication with the control plane. Your cluster has been set up to operate in a specific manner. The command plane ensures that it does.
2. **Nodes**: These devices carry out the tasks assigned to them by the control plane.There must be at least one compute node in a Kubernetes cluster, however typically there are many. On nodes, pods are orchestrated and scheduled to operate. Do you need to increase the cluster's capacity? Expand the nodes.
3. **Pod**: A collection of one or more containers that have been deployed on a single node. A pod's containers share an IP address, IPC, a hostname, and other resources. Pods abstract the underlying container's network and storage. This makes it easier to relocate containers around the cluster.The smallest and most basic unit in the Kubernetes object model is a pod. A single instance of an application is what it represents. A container or a group of closely related containers, combined with settings that control how the containers are run, make up each pod. To run stateful applications, pods can be attached to persistent storage.
4. **Service**: This separates work definitions from pods. Kubernetes service proxies route service requests to the correct pod, regardless of where it moves in the cluster or if it has been replaced.
5. **Replication controller**: This determines how many identical copies of a pod should be operating on the cluster.
6. **Kubelet**: This service runs on nodes, reads container manifests, and guarantees that the specified containers start and execute.
7. **kubectl**: The command line configuration tool for Kubernetes.

## Kubernetes Clusters

Groups of hosts running Linux containers can be grouped together, and Kubernetes makes managing these clusters simple and effective. A working Kubernetes deployment is called a cluster.

The design of a Kubernetes cluster is based on 3 principles:

* **Secure.** It must to adhere to the most recent security best practises.
* **Easy to use.** It should be manageable with a few straightforward instructions.
* **Extendable.** It should be adaptable from a configuration file and not favour any particular supplier.

## How does Kubernetes work?

The *Kubernetes cluster* is a functional Kubernetes setup. The control plane and the compute nodes, or machines, can be seen as the two distinct components of a Kubernetes cluster.

Each node, which can either be a physical or virtual system, has its own Linux environment. Pods, which are composed of containers, are executed by each node.

The cluster's desired state, including the applications that are active and the container images they utilise, must be maintained by the control plane. Applications and workloads are really run on compute machines.

On top of an operating system, Kubernetes communicates with pods of running containers on the nodes.

An administrator issues commands to the Kubernetes control plane, which then transmits those directives to the compute machines.

This handoff uses a variety of services to determine which node is most appropriate for the task automatically. The desired task is subsequently assigned to the node's pods when resources have been allocated.

The desired state of a Kubernetes cluster specifies which workloads or apps should be running together with the images they should use, the resources they should have access to, and other similar configuration information.

Little has changed in terms of infrastructure when it comes to managing containers. Simply put, you have more control over containers since you can manage them at a higher level without having to handle every individual container or node individually.

It's up to you where you run Kubernetes. This can be done on physical servers, virtual machines, public clouds, private clouds, and hybrid clouds. One of Kubernetes' main benefits is that it can be used with a variety of infrastructure types.

## Benefits of Kubernetes-native infrastructure

* Agility and simplicity of the public cloud on-premises to lessen conflict between IT operations and developers.
* saving money by not requiring a separate hypervisor layer to run virtual machines.
* Kubernetes gives developers the freedom to scale infrastructure and applications by deploying containers, serverless applications, and VMs.
* Extensibility of the hybrid cloud using Kubernetes as the foundational layer for both private and public clouds.

## Why do we need Kubernetes?

You can distribute and manage containerized, legacy, cloud-native, and apps that are being refactored into microservices with the aid of Kubernetes.

You can create application services that use numerous containers, schedule those containers across a cluster, scale those containers, and keep track of their long-term health using this technology. You can effectively move toward improved IT security with Kubernetes.
