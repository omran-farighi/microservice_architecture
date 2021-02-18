# Virutal Machines

### Pros:
* Ephemeral machines: quick to create and destroy a virtual machine when finished using it
* Low headspace: doesn't require manual management and configuration of cables, everything is programmable and virutalized
* Can be moved from machine to machine

# Containers

### Pros
* Less wasteful: don't require large chunks of RAM and disk
* Lightweight: don't require the entire OS
* Only runs processes related to software
* Lack of dependency: each container has its own copy of packages, libraries, and other supporting files

### Physical over Virtual

While virtual machines have clear advantages over physical machines, there are times when those advantages are not fully realized. If a 
a different OS is not required, it wouldn't make sense to run a virutal machine. Just use the physical machine so that the resources aren't
uncessarily split between two of the same OS. Virtual machines also do not allow you to use any empty RAM space, further restricting yourself 
of resources. It may also help to use a physical machine for security purposes. A virtual machine can be moved from machine to machine and 
doesn't have any headspace where as a physical machine is difficult to move. 
