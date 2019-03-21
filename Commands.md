
#### Commands used for kinesis.

* Create Stream

        aws kinesis create-stream --stream-name AppStream --shard-count 1
        aws kinesis list-streams
        aws kinesis describe-stream --stream-name AppStream
        aws kinesis put-record --stream-name AppStream --partition-key 123 --data "hello"
        aws kinesis list-shards
        
        aws kinesis get-shard-iterator --shard-id sharid 000000000 --shard-iterator-type TRIM_HORIZN --stream-name AppStream
        
      
        