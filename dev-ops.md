# Dev Ops

http://explainshell.com/explain?cmd=rsync+-p+--chmod%3D%2Brwx+-e+%22ssh+-i+userserver.pem%22+--copy-unsafe-links+-rz+user%40server%3A~%2F+%2Fdb_backups%2Fwww%2F

### Tmux cheat sheet
https://gist.github.com/MohamedAlaa/2961058

### Reverse/Service Proxies
- http://www.haproxy.org/
- http://nginx.com/resources/admin-guide/reverse-proxy/
- https://github.com/vektra/templar

Deployment Infrastructure 
============================
* [Docker](https://www.docker.com/) - container tooling
  * [Fig](http://www.fig.sh/) - YAML+tool glue to create groups of containers
  * [docker-gen](https://github.com/jwilder/docker-gen) - tool to render config templates based on containers (e.g. log rotation)
  * [Gaudi](https://github.com/marmelab/gaudi) similar to Marathon, it links docker images together over a grid of machines.  It has a very neat UI for linking them together. 
  * [docker-gen] https://github.com/jwilder/docker-gen 
  * [kubernetes] https://github.com/GoogleCloudPlatform/kubernetes 
     * [Borg the predecessor to Kubernetes] http://kubernetesio.blogspot.com/2015/04/borg-predecessor-to-kubernetes.html &  https://research.google.com/pubs/pub43438.html
  * [docker CI/Build/Deployment] https://www.shippable.com - CI server with docker support and builds docker containers with results.

* Service Discovery/Configuration 
  * [Consul](http://www.consul.io/intro/index.html)
  * [SmartStack](http://nerds.airbnb.com/smartstack-service-discovery-cloud/) 
  * [Mesos/Marathon] @See below in Task Distribution frameworks.  
  * [confd](https://github.com/kelseyhightower/confd) - writes config files out of consul or etcd
* Deployment
  * [goauto] (https://github.com/dshills/goauto) - scripted go builds with file watching, all pure go.
  * [Goship](https://github.com/gengo/goship) Simple deployment tool similar to Jenkins/Travis written in Go.  Also has a [fantastic logo!](https://camo.githubusercontent.com/33a7d9a138ac73ece82dee977c216eb13dffc984/687474703a2f2f692e696d6775722e636f6d2f524c766b486b612e706e67)

* Blogs, Research and Methods
  * http://roc.cs.berkeley.edu/papers/recursive_restartability.pdf
  * http://blog.appsdeck.eu/post/105609534953/graceful-server-restart-with-go

### Key Management 
- https://github.com/cloudflare/redoctober - Go server for two-man rule style file encryption and decryption.
- https://github.com/hbs/oss - 

### Log Management 
- https://github.com/lytics/sshtail - tails a log file from multiple machines 


