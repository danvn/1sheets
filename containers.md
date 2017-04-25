# Containers
Containers are a method of **operating system virtualization** that allow for applications and their dependencies to run in **resource-isolated processes**.

Containers are by far, the most associated with **Docker**, but other Container technologies are rising, like Amazon EC2 Container Service, Microsoft Azure Container Service, LXC, LXD, Solaris Zones, RKT, and BSD Jails.

## What does Containers Solve?
- Package an application's building blocks (code, configurations, dependencies) 
	- version control
- Ensure that applications deploy...
	- quickly 
	- reliably
	- consistently
- Container Stengths
	- Environment Consistency
		- Portability of dependencies
		- less technical friction moving applications throguh development 

## Competitors
- Virtual Machines 

![Docker vs. VM's](http://tech.paulcz.net/presentation-just-enough-docker-for-openstack/images/docker-vs-vm.png)

## Containers's Role in the Technology Landscape
- Distributed Applications and Microservices 
	- Breaking your application into independent tasks (microservices)
	- Separate containers for webserver, application server, message queue, etc.
	- Each component runs on its own *docker image*
- Running apps over Docker Containers and **deploying anywhere**

- Continuous Integration 
	- Docker image versioning
- Continuous Deployment
	- Pull new image version, test, deploy

## Challenges with Containers
- Security 
	- Root access to machine they are on 
- Containers are less isolated from other containers than VM's are isolated to other VM's 
- Less flexibility in Operating Systems

## Where did Containers come from?
- Need for speed
- Continuous and consistent deployment and integration


## Related Technologies
- [Cluster Managers](/Kubernetes.md) 


## What applications, software or websites use Containers? [(lots)](https://www.docker.com/customers)
- Google Search
- Google App Engine
- Twitter
- ADP
- Paypal
- Bleacher Report
- Spotify

## Future of Containers
- Containers have more potential than VM's 
![Docker Adoption is on the Rise](https://datadog-live.imgix.net/img/docker-2017-3_v3.png)