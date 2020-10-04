# ElasticDump

Download an entire Elastic cluster with one command.

## Parameters

```go
  -minDocCount uint
    	Minimum number of Documents for each index (default 100)
  -minIndexSizeKB uint
    	Minimum size of index for dump (default 1024)
  -targetIP string
    	Target IP Address
  -targetPort uint
    	Target port (default 9200)
```

## TODO
- Compression
- The ability to upload artifacts to S3/Wasabi/B2
- Index pattern filter
- TLS support
- More parameter customization and optimization (Scroll size, thread count, artifact folder)
