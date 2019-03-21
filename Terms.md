####  Concepts

  * Steams:
    
        Unit of data: data record
        Stream: group of data records
        The data records in a stream are
        distributed into shards
        
   * Producers
   
         A producer puts data records into stream
        
   * Consumers
   
         A consumer gets data from Kinesis.
        
        
   * Shards
        
         Unique identify sequence of data records in a stream
         One or more shards=stream
        
   * PartitionKey
   
         Groups data by shard within a stream
         Partition key determines which shard a data
         record belongs to.
         Partition keys are Unicode string with a maximum
         length limit of 256 bytes.
         Application must specify a partition key when putting 
         data into a stream.
        
   * Limitations
   
        A single shard can ingest up to 1 MiB of data per second
        The default shard limit is 500 shards for the
        following regions: N. Virginia, Oregon and Ireland.
        All other regions default shard limit is 200 shards.