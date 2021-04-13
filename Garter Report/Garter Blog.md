# Microservices

Microservice architecture (MSA) is an innovated application architecture because it enables agility and scalability. Its infrastructure
provides an enviornment for running and managing the fine graind application components. These components are strongly encapsulated and are loosely
coupled so they are indpenedently deployable and scalable. The fully realize the benefits of MSA, there are five components on which it depends on:
a managed container system, a service mesh, an API gateway, observability services, and backing services.

# Building Blocks
* ## Managed container system
  Host for microservices
  
* ## Service mesh
  Enables microservices to communicate with each other
  
* ## API gateway
  Layer that manages access to services running in the containr environment
 
* ## Observablitiy services
  Support monitoring, alerting, logging, and diagnostics
  
* ## Backing services
  Support persistence, caching, and event management
  
  
  [insert image here]
  
  The image above shows the flow of how the MSA runtime infrastructre is set up. In order for any service, app, or device to gain access
  to the managed containr system where the application component is being run, the API gateway must first authenticate access. The container
  that the microservice is being hosted on relies on backing services to maintain functionality. It can also be maintained by the developers
  using the observability services. This allows them to monitor, alert, log, or run diagnostics on the container.
