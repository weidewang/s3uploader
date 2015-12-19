# Browser Uploads to S3 using HTML POST Forms


## set env
```
export AWS_ACCESS_KEY_ID=<YOUR AWS_ACCESS_KEY_ID>
export AWS_SECRET_ACCESS_KEY=<YOUR AWS_SECRET_ACCESS_KEY>
export AWS_REGION=<YOUR AWS_REGION>
```

## run
`go run s3uploader.go` 

open browser access http://127.0.0.1:8000/


change bucket and port

see  `go run s3uploader.go -h` usage