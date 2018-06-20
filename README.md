# pylel-container
Easy distribution of python classes across servers.

The main objective of this repository is to remove the burden of having to write parallel code across remote machines everytime we want to massively use a certain python class (which might be a container of different degrees of complexity, problably requiring its own memory space).

In a macro level, the framework should enable to wrapp a python container as a class and use it (as it was local) across remote servers with proper logging for debugging purposes.

# Key features

The main points are as follows:

- Pass a class to a pylel manager and use it as locally.
- Update asynchrnously and responsively.
- To be used with any type of container, with simulations/environments or other types of logic in mind.  
