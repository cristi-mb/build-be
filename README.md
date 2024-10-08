# build-be

### Inputs:

| Name  | Required | Details | Default value |
| :-----: | :---: | :--------: | :----: |
| aws-access-key | yes | | |
| aws-secret-access-key | yes | | |
| aws-region | no | | `us-east-1` |
| ecr-repository | yes | | |
| slack-channel | no | Send to enable Slack messages | `''`|
| slack-token | no | Send to enable Slack messages | `''` |
| docker-path | no | Path to the folder containing the Dockerfile | `./` |
| submodules | no | `true` if there are submodules in the repository that need to be initialised | |
| submodules-key | no | Required if submodules is `true` and the submodule repositories are private | |
| custom-tag-tag | no | Override default image tag | `''` |
| tag-prefix | no | Append additional info to image tag (before commit hash) | `''` |
| tag-suffix | no | Append additional info to image tag (after commit hash) | `''` |

<br>

### Outputs:

- **image-tag**: Tag of the Docker image published to the ECR repository
