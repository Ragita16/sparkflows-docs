AWS : Assume Roles
====

Fire Insights can be configured with assume roles.

Below are some Troubleshooting steps:


IOException: ''Unset property fs.s3a.assumed.role.arn''

::

    java.io.IOException: Unset property fs.s3a.assumed.role.arn
  at org.apache.hadoop.fs.s3a.auth.AssumedRoleCredentialProvider.<init>(AssumedRoleCredentialProvider.java:76)
  at sun.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
  at sun.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
  at sun.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
  at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
  at org.apache.hadoop.fs.s3a.S3AUtils.createAWSCredentialProvider(S3AUtils.java:583)
  at org.apache.hadoop.fs.s3a.S3AUtils.createAWSCredentialProviderSet(S3AUtils.java:520)
  at org.apache.hadoop.fs.s3a.DefaultS3ClientFactory.createS3Client(DefaultS3ClientFactory.java:52)
  at org.apache.hadoop.fs.s3a.S3AFileSystem.initialize(S3AFileSystem.java:252)
  at org.apache.hadoop.fs.FileSystem.createFileSystem(FileSystem.java:3354)
  at org.apache.hadoop.fs.FileSystem.get(FileSystem.java:474)
  

1. Make sure the role works and the user trying to enter it can do so from AWS the command line before trying to use the S3A client.
2. Try to access the S3 bucket with reads and writes from the AWS CLI.


Reference guide : https://hadoop.apache.org/docs/stable/hadoop-aws/tools/hadoop-aws/assumed_roles.html#Troubleshooting_Assumed_Roles
