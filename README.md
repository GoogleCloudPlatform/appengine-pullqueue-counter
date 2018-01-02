appengine-pullqueue-counter
===========================

A simple counter with App Engine pull queue

To deploy:
```
$gcloud app deploy app.yaml worker.yaml queue.yaml 
```

To view default service log:
```
~/google-cloud-sdk/bin/gcloud app logs tail -s default
```

To view worker service log:
```
~/google-cloud-sdk/bin/gcloud app logs tail -s worker
```