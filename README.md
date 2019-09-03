## AWS KMS Post-quantum TLS Example

Demo code to setup the Java SDK 2.0 to use Post-quantum TLS with KMS. See [this blog post](https://aws.amazon.com/blogs/security/using-post-quantum-tls-with-kms/) for more info.

### Prequesites
1. Maven installed
1. AWS credentials setup for your platform, see [Set Up AWS Credentials for Development](https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/setup-credentials.html).
### Running the example
```$bash
$ git clone https://github.com/aws-samples/aws-kms-pq-tls-example.git
$ cd aws-kms-pq-tls-example
$ mvn package
$ java -jar target/aws-kms-pq-tls-example-1.0-jar-with-dependencies.jar
```
## License Summary

This sample code is made available under the MIT-0 license. See the LICENSE file.
