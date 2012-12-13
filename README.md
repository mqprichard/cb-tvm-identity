cb-tvm-identity
===============

CloudBees/Maven version of Amazon STS Identity Token Vending Machine service

Use the CloudBees RUN SDK to set the following config params:
* bees config:set -a cb-tvm-identity AWS_ACCESS_KEY_ID=&lt;TVMUser_AccessKey&gt;
* bees config:set -a cb-tvm-identity AWS_SECRET_KEY=&lt;TVMUser_SecretKey&gt;
* bees config:set -a cb-tvm-identity PARAM1=&lt;APP_NAME&gt;

See [this blog](http://blog.cloudbees.com/2012/12/amazon-web-services-and-platform-as_12.html) for details of how to configure the Token Vending Machine and iOS/Android clients
