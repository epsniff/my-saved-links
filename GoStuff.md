### Go Scripting engines
#### Embeddable 
- https://github.com/mattn/anko - Go like scripting lang.
- https://github.com/robertkrimen/otto - javascript engine
#### Bindings 
- https://github.com/sbinet/go-python 

#### go in a browser 
https://github.com/gopherjs/gopherjs

### CLI/Terminal helpers
https://github.com/alecthomas/kingpin - command line parsing
https://github.com/gonuts/commander - command line parsing

https://github.com/peterh/liner - interactive helpers, like vim.

### Guides
- http://peter.bourgon.org/go-in-production/ - using go in production.
- http://www.cs.columbia.edu/~aho/cs6998/reports/12-12-11_DeshpandeSponslerWeiss_GO.pdf proposed Go scheduler changes. 


### Data Storage/Caching 
- https://github.com/stretchr/hoard/ - go cach'ing
- http://bazil.org/doc/ - Go FUSE filesystem framework.

### Communication and Serlization 
- https://github.com/grpc/grpc-go - Protobuf v3 introduces RPC :)
- https://github.com/pquerna/ffjson faster json using structs.  Requires an extra build step.
- https://github.com/gdamore/mangos - zmq like messaging libary in pure go.
- https://github.com/apcera/gnatsd -- Go nats server.  according benchmarks is almost as fast as brokerless message systems like zmq.
- https://github.com/glycerine/go-capnproto - capnproto serialization in go. 
- https://github.com/google/flatbuffers/tree/master/go - flatbuffer serialization
- https://github.com/jpillora/chisel - allows you to use an HTTP connection as a TCP socket, for tunneling through a firewall. 

### DSLs, Code Gen
- https://github.com/araddon/qlparser - Go parser. 
- http://clipperhouse.github.io/gen/ - Go Generator example
- design patterns in Go https://github.com/monochromegane/go_design_pattern

#### SMTP Server in go
- https://github.com/flashmob/go-guerrilla
- https://github.com/bradfitz/go-smtpd

#### Future Golang changes. 

https://docs.google.com/document/d/1wmjrocXIWTr1JxU-3EQBI6BK6KgtiFArkG47XK73xIQ/preview?sle=true# - Go 1.5 GC changes 
