My personal technology radar
===================
I use to keep all my links on emerging technology, UX, dev-ops and papers in Google Docs.  While this was helpful for me, it wasn't useful for anyone else trying to do the same research I had already done.  So Im experimenting with moving those links into a Github repo.  

Now that this stuff is public facing though, I should really replace my shorthand notes with better discriptions :p.

Github octocat images: https://octodex.github.com/

## Distributed/Infrastructure Engineering
- https://github.com/lytics/metafora

# Data Engineering
- Raft consensus algorithm. 
   - Paper:  http://ramcloud.stanford.edu/raft.pdf  
   - Animated walk through of how raft works:http://thesecretlivesofdata.com/raft/
- Streaming Raft as implmented in influxDB: https://github.com/influxdb/influxdb/pull/903

### Data Science: 
- https://github.com/harrisj/punkt - sentence tokenizer in Go
- https://github.com/lytics/anomalyzer - Probabilistic anomaly detection in Go. 
- https://github.com/drewlanenga/multibayes - Multiclass naive Bayesian document classification in Go
- https://bitbucket.org/tebeka/snowball/src - Snowball stemmer in Go
- https://github.com/reiver/go-porterstemmer - porter stemmer in Go
- https://github.com/dgryski/go-topk - ktop in go Or https://gowalker.org/github.com/cloudflare/golibs/spacesaving which is topk using the space-saving algorithm. 
- https://github.com/bobhancock/goxmeans - xmeans

### Data Storeage: 
https://www.youtube.com/watch?v=jI3LiKhqN0E - Cockroachdb spanner port, that uses raft and rocksdb.  Supports range scans and transactions. 

##### Time Series Database

- http://influxdb.com/ - time series database, it uses streaming raft for consensus


##### Graph Databases
- https://github.com/google/cayley
- https://github.com/orientechnologies/orientdb
- http://thinkaurelius.github.io/titan/ 

### Distributed Filesystems 
- HDFS :p 
- https://github.com/pachyderm-io/pfs - docker based distributed filesystem. 
- https://code.google.com/p/weed-fs/ 

# Random
- https://github.com/araddon/qlparser - This is a [x]QL generic lexer parser, that should be useful for constructing Dialect Specific Lexer/Parsers.

### Go Scripting engines

#### Embeddable 
- https://github.com/mattn/anko - Go like scripting lang.
- https://github.com/robertkrimen/otto - javascript engine

#### Bindings 
- https://github.com/sbinet/go-python 

### Random Go Stuff
- https://github.com/buger/goterm This library provides basic building blocks for building advanced console UIs in go.
- http://www.cs.columbia.edu/~aho/cs6998/reports/12-12-11_DeshpandeSponslerWeiss_GO.pdf proposed Go scheduler changes. 
- https://github.com/pquerna/ffjson faster json using structs.  Requires an extra build step.

### IRC Client
 - http://ubuntuforums.org/showthread.php?t=1010780 - IRC is still the best way to talk shop.
 - https://kiwiirc.com/docs/installing/config - Webbased IRC channel
 - https://www.irccloud.com/ 
