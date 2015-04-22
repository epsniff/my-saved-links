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

##### Data Science: 
- https://github.com/harrisj/punkt - sentence tokenizer in Go
- https://github.com/lytics/anomalyzer - Probabilistic anomaly detection in Go. 
- https://github.com/drewlanenga/multibayes - Multiclass naive Bayesian document classification in Go
- https://bitbucket.org/tebeka/snowball/src - Snowball stemmer in Go
- https://github.com/reiver/go-porterstemmer - porter stemmer in Go
- https://github.com/dgryski/go-topk - ktop in go Or https://gowalker.org/github.com/cloudflare/golibs/spacesaving which is topk using the space-saving algorithm. 
- https://github.com/bobhancock/goxmeans - xmeans
- http://blog.sense.io/introducing-sense-a-platform-for-data-science/ 
- https://github.com/skelterjohn/go.matrix - a good matrix math package for Go.

##### Data Storeage: 
- Aerospike: a fast in memory database, simple to setup.  Seems to be a C,P CAP db.  It also supports a hybrid mode were only indexes are in-memory and data is stored on disk.
    - https://www.aerospike.com/docs/client/go/usage/ldt/ldt.html
    - http://www.aerospike.com/when-to-use-aerospike-vs-cassandra/ 
- https://www.youtube.com/watch?v=jI3LiKhqN0E - Cockroachdb spanner port, that uses raft and rocksdb.  Supports range scans and transactions. 
- Cassandra stuff : 
   - https://github.com/hailocab/ctop - quick overview of cassandra's state.

- http://www.hyflow.org/hyflow-go/ - need to read more about it.. looks cool
- Bleve https://github.com/blevesearch/bleve - Go Full Text indexing libary 
- sqlx https://github.com/jmoiron/sqlx - ORM like lib for golang

##### Time Series 
- http://influxdb.com/ - time series database, it uses streaming raft for consensus
- http://godoc.org/github.com/codahale/hdrhistogram - Package hdrhistogram provides an implementation of Gil Tene's HDR Histogram data structure. The HDR Histogram allows for fast and accurate analysis of the extreme ranges of data with non-normal distributions, like latency.
- https://github.com/rcrowley/go-metrics
-
##### Graph Databases
- https://github.com/google/cayley
- https://github.com/orientechnologies/orientdb
- http://thinkaurelius.github.io/titan/ 

##### Distributed Filesystems 
- HDFS :p 
- https://github.com/pachyderm-io/pfs - docker based distributed filesystem. 
- https://code.google.com/p/weed-fs/ 

# Data Visualization:
- D3.js
   - learning d3
      - https://github.com/mbostock/d3/wiki/Tutorials
      - http://www.recursion.org/d3-for-mere-mortals/  
      - http://www.jeromecukier.net/blog/2012/09/04/getting-to-hello-world-with-d3/
      - http://bost.ocks.org/mike/
      - http://shop.oreilly.com/product/0636920025429.do - book
- https://code.google.com/p/plotinum/wiki/Examples - Go based 

# Random

- https://github.com/araddon/qlparser - This is a [x]QL generic lexer parser, that should be useful for constructing Dialect Specific Lexer/Parsers.


### Go Scripting engines

#### Embeddable 

- https://github.com/mattn/anko - Go like scripting lang.
- https://github.com/robertkrimen/otto - javascript engine

#### Bindings 

- https://github.com/sbinet/go-python 

### Random Go Stuff
- https://github.com/PuerkitoBio/purell - simple go lib to normlize urls
- https://github.com/buger/goterm This library provides basic building blocks for building advanced console UIs in go.
- https://github.com/go-stack/stack/blob/344948d226e07e93dcda17055d9d78252e6d2c3f/stack.go#L48 - Example of using a custom string formater 
- https://github.com/nsf/termbox-go - for creating ascii termials Angband anyone?
   - https://code.google.com/p/termbox/  same thing but not pure go
- https://github.com/gizak/termui - terminal graphics and data visulization.s 

### IRC Client
 - http://ubuntuforums.org/showthread.php?t=1010780 - IRC is still the best way to talk shop.
 - https://kiwiirc.com/docs/installing/config - Webbased IRC channel
 - https://www.irccloud.com/ 
