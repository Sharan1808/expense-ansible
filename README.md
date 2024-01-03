# sharan1808/expense-ansible

```json

{
   "Version": "2012-10-17",
   "Statement": [
       {
           "Effect": "Allow",
           "Principal": {
               "AWS": "arn:aws:iam::314523829041:role/frontend"
           },
           "Action": "s3:PutObject",
           "Resource": "arn:aws:s3:::d76s-prometheus-alert-rules/*"
       }
   ]
}
```

