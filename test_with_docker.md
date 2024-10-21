


docker run --publish 80:80 --env S3PROXY_AUTHORIZATION=none --env JCLOUDS_PROVIDER=azureblob --env JCLOUDS_AZUREBLOB_AUTH=azureKey --env JCLOUDS_IDENTITY=mead0blob0storage --env JCLOUDS_CREDENTIAL=eTN4U4Qp22VeTiA55F1N0zSUlKuSSX24wR3l9tN77P6glc2Z1M1Bjt0d4tZeIRPbA1//AomdiOdf+AStfFk2fQ== --env JCLOUDS_ENDPOINT=https://mead0blob0storage.blob.core.windows.net/  andrewgaul/s3proxy:master


curl http://127.0.0.1:80/  

