# build-be

### Inputs:

| Name  | Required | Details | Default value |
| :---: | :------: | :-----: | :-----------: |
| aws-access-key | yes | | |
| aws-secret-access-key | yes | | |
| aws-region | yes | | |
| slack-channel | no | `true` to enable Slack messages | `''`|
| slack-token | no | `true` to enable Slack messages | `''` |
| ecr-repository | yes | | |
| docker-path | no | | `./` |
| submodules | no | `true` if there are submodules in the repository that need to be initialised | |
| submodules-key | no | Required if submodules is `true` and the submodule repositories are private | |

<br>

### Outputs:

- **image-tag**: Tag of the Docker image published to the ECR repository
