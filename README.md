# terragrunt-awscli

This is a lightweight docker image that extends the [alpine/terragrunt](https://hub.docker.com/r/alpine/terragrunt) image to include `aws-cli`

This image is primarily used for [GitLab](https://gitlab.com/paulmarsicloud/openvpn-ephemeral-template), [GitHub Actions](https://github.com/paulmarsicloud/openvpn-ephemeral-github-actions-template) and [CircleCI](https://github.com/paulmarsicloud/openvpn-ephemeral-circleci-template/) pipelines that create OpenVPN EC2 instances in automation using the [paulmarsicloud/openvpn-ephemeral/aws](https://registry.terraform.io/modules/paulmarsicloud/openvpn-ephemeral/aws/latest) Terraform Module.
