Printing Code
==============

Jekyll site for printingcode.runemadsen.com.


Deployment
----------

Run this to deploy to S3:

```bach
s3cmd sync --delete-removed --guess-mime-type --cf-invalidate --acl-public _site/ s3://silenceisavirus.com
```