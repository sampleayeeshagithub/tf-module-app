# sampleayeeshagithub/tf-module-app

```bash
aws kms create-grant \
  --region us-east-1 \
  --key-id arn:aws:kms:us-east-1:299627189740:key/20d4c346-4cde-4977-b03b-c758bef825a5 \
  --grantee-principal "arn:aws:iam::299627189740:role/aws-service-role/autoscaling.amazonaws.com/AWSServiceRoleForAutoScaling" \
  --operations "Encrypt" "Decrypt" "ReEncryptFrom" "ReEncryptTo" "GenerateDataKey" "GenerateDataKeyWithoutPlaintext" "DescribeKey" "CreateGrant"
```



