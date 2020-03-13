# aws-ssm-secureString-CF

This is a demo of a custom resource template to create secure string in AWS SSM Parameter Store, AWS do not support the creation of secureString with Cloudformation Templates by default, feel free to use this code example.

## Deploy

To deploy it in AWS you should keep the following order:
```
kms-Key.yml
customResource-paramStoreHelper.yml
ssm-paramStore-Variables.yml
```