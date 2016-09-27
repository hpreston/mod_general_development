### Why do we care

In development today, it is not only good practice, but it's expected to provide software with dependency isolation.  If you're building a python application that will be downloaded and ran on a host, virtualenv for python is a standard way to do this.  

However, more and more applciations are being packaged in containers (typically Docker containers) which provide a level of isolation even higher than a simple Virtual Environment.  You could create a Virtual Environment within a container, but if you are practicing good container strategy, that is likely not needed as part of final delivery.  

Though, in the development phase, you may choose to use virtualenv to develop within to avoid the extra steps of rebuilding a new container for every update and test.

