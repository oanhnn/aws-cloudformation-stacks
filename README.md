# oanhnn/aws-cloudformation-stacks

[![Build Status](https://travis-ci.org/oanhnn/aws-cloudformation-stacks.svg?branch=master)](https://travis-ci.org/oanhnn/aws-cloudformation-stacks)

## Templates

- [x] [SNS Alert](docs/templates/alert.md)
- [x] [VPC](docs/templates/vpc.md)
- [x] [S3 Bucket](docs/templates/s3-bucket.md)
- [x] [VPC Endpoint to S3](docs/templates/s3-endpoint.md)
- [x] [Client Security Group](docs/templates/client-sg.md)
- [x] [Bastion](docs/templates/bastion.md)
- [x] [Aurora with MySQL Engine](docs/templates/aurora-mysql.md)
- [x] [ElastiCache with Redis Engine](docs/templates/elasticache-redis.md)

## Stacks

| Stack                                     | Actions |
|-------------------------------------------|---------|
| [Common stack](docs/stacks/common.md)     | [![Launch Stack](docs/img/launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=common-stack&templateURL=https://s3-ap-southeast-1.amazonaws.com/oanhnn-aws-cfn/master/stacks/common.yml) |

## Contributing

All code contributions must go through a pull request and approved by a core developer before being merged. 
This is to ensure proper review of all the code.

Fork the project, create a feature branch, and send a pull request.

If you would like to help take a look at the [list of issues](https://github.com/oanhnn/aws-cloudformation-stacks/issues).

## License

This project is released under the MIT License.   
Copyright © 2018 [Oanh Nguyen](https://github.com/oanhnn)   
Please see [License File](https://github.com/oanhnn/aws-cloudformation-stacks/blob/master/LICENSE) for more information.
