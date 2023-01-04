# build-be

### Inputs:

| Name  | Required | Details | Default value |
| :---: | :------: | :-----: | :-----------: |
| aws-access-key | yes | | |
| aws-secret-access-key | yes | | |
| aws-region | yes | | |
| slack-channel | yes | | |
| slack-token | yes | | |
| ecr-repository | yes | | |

<br>

### Outputs:

- **image-tag**: Tag of the Docker image published to the ECR repository
