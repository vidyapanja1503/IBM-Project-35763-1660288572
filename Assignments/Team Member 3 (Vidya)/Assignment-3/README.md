

Create a `.env` file and type down the important credentials for IBM Bucket.

It would look like this:

```python
COS_ENDPOINT="s3.tok.ap.cloud-object-storage.appdomain.cloud"
COS_API_KEY_ID="knvrm3v_UOB2OPaNoH31zjcszrFsWO729xjXpkZEtkoY"
COS_INSTANCE_CRN="https://v2hospital.s3.jp-tok.cloud-object-storage.appdomain.cloud/index.html"
```

Don't worry, this is not the real credentials of mine, just placeholders ;)

You can find these credentials under your IBM Cloud Storage Bucket Service Credentials. 
If you can't find them then you have to create the Service Credentials first. 
Also make sure to give public access to the objects inside your Bucket.

Place the `.env` file in the root folder and you're good to go.
