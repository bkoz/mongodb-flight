# mongodb-flight

## GPS data

### mongoimport

Import into MongoDB Atlas

```
mongoimport --host Cluster0-shard-0/cluster0-shard-00-00-rcrnv.mongodb.net:27017,cluster0-shard-00-01-rcrnv.mongodb.net:27017,cluster0-shard-00-02-rcrnv.mongodb.net:27017 --ssl --username bkozdemba --authenticationDatabase admin --db simple --collection tracks --type json --file flight-geo.json
```
