# Building AMI using Packer

## Packer command

```bash
    $ packer validate ubantu-ami.json
    $ packer build \
    -var 'aws_access_key=REDACTED' \
    -var 'aws_secret_key=REDACTED' \
    -var 'aws_region=us-east-1' \
    ubantu-ami.json
```