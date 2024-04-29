# Load balancing
Load balancing is the practice of distributing computational workloads between two or more computers. On the Internet, load balancing is often employed to divide network traffic among several servers. This reduces the strain on each server and makes the servers more efficient, speeding up performance and reducing latency. Load balancing is essential for most Internet applications to function properly.

Imagine a checkout line at a grocery store with 8 checkout lines, only one of which is open. All customers must get into the same line, and therefore it takes a long time for a customer to finish paying for their groceries. Now imagine that the store instead opens all 8 checkout lines. In this case, the wait time for customers is about 8 times shorter (depending on factors like how much food each customer is buying).

Load balancing essentially accomplishes the same thing. By dividing user requests among multiple servers, user wait time is vastly cut down. This results in a better user experience — the grocery store customers in the example above would probably look for a more efficient grocery store if they always experienced long wait times.

Load balancing is handled by a tool or application called a load balancer. A load balancer can be either hardware-based or software-based. Hardware load balancers require the installation of a dedicated load balancing device; software-based load balancers can run on a server, on a virtual machine, or in the cloud. Content delivery networks (CDN) often include load balancing features.

When a request arrives from a user, the load balancer assigns the request to a given server, and this process repeats for each request. Load balancers determine which server should handle each request based on a number of different algorithms. These algorithms fall into two main categories: static and dynamic.

Where is load balancing used?
As discussed above, load balancing is often used with web applications. Software-based and cloud-based load balancers help distribute Internet traffic evenly between servers that host the application. Some cloud load balancing products can balance Internet traffic loads across servers that are spread out around the world, a process known as global server load balancing (GSLB).

Load balancing is also commonly used within large localized networks, like those within a data center or a large office complex. Traditionally, this has required the use of hardware appliances such as an application delivery controller (ADC) or a dedicated load balancing device. Software-based load balancers are also used for this purpose.
