Chapter 6
* Kubernetes volumes
* emptyDir: useful for sharing volumes between containers running the same pod
* gitRepo: clone repo into pod on startup (deprecated)
* hostPath: mount directory from host filesystem. Not recommended because no guarantees about host usually
* must be relative