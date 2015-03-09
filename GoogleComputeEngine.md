Google Cloud Logging : https://cloud.google.com/logging/docs/
- https://cloud.google.com/logging/docs/install/compute_install - steps for using google's log collections service.  

Google Cloud Monitoring : https://cloud.google.com/monitoring/docs 
- Installing Machine Agents https://cloud.google.com/monitoring/agent/install-agent
- Installing Service Agents (kafka, ElasticSearch, etc..) https://cloud.google.com/monitoring/agent/


Google Storeage API: 
- https://github.com/google/google-api-go-client/tree/master/storage/v1 - This SDK is primaryly for working with GCS as a key/value store.  i.e. the GCS-JSON REST api.  Its a bit hard to work with for using GCS for files.
- https://code.googlesource.com/gocloud/+/master/storage/storage.go - I find this SDK much easier to work with... Once you figure out how to convert a the ServiceAccount's P12 token into a JWT token.  And then figure out how to create the JWT transporter :/  Anyway, it provides much lowerlevel apis and stream-reader/writers for reading large BLOBs. 
  
