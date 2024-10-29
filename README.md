# hsa-s3

# Task
Simple Storage

Create bucket where objects can’t be modified and all requests are logged.

# Solution

1. Create bucket
   1. ![](./proofs/create_bucket_1.png)
   2. ![](./proofs/create_bucket_2.png)
   3. ![](./proofs/create_bucket_3.png)
   4. ![](./proofs/bucket_created_1.png)
2. Config bucket Object Lock
   1. ![](./proofs/object_lock_1.png)
   2. On attempt to upload file with the same name its version created ![](./proofs/versioned_file.png)
3. (Optional) Config ACL to allow external read access to files
   1. ![](./proofs/acl_enabled.png)
   2. ![](./proofs/saved_objects_accessible_1.png)
4. Config logging
   1. ![](./proofs/logging_config.png)
   2. ![](./proofs/logs_bucket_created.png)
   3. ![](./proofs/logs_arrived.png)
   4. ![](./proofs/log_contents.png)