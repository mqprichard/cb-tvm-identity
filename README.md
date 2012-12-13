cb-tvm-identity
===============

CloudBees/Maven version of Amazon aws-tvm-identity Token Vending Machine service

Use the CloudBees RUN SDK to set the following config params:
*bees config:set -a aws-cb-tvm-identity AWS_ACCESS_KEY_ID=<TVMUser_AccessKey>
*bees config:set -a aws-cb-tvm-identity AWS_SECRET_KEY=<TVMUser_SecretKey>
*bees config:set -a aws-cb-tvm-identity PARAM1=<APP_NAME>

See [this blog](http://blog.cloudbees.com/2012/12/amazon-web-services-and-platform-as_12.html) for details of how to configure the Token Vending Machine and iOS/Android clients
