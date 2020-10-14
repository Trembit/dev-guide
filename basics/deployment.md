### Deployment

## AWS

TBD

Usual stack: ECS, ECR, CodeBuild, CloudFront, S3, Route53. All this delivered via Terraform.

Unusual stack #1: Beanstalk

Unusual stack #2: AppSync


## Bare metal

TBD

We use Traefik for deployment to raw linux servers. It is good reverse proxy / load balancer with HTTPS certificate generation.

## Other

Heroku is awesome as deploy and forget solution, but it doesn't usually fit into customer stack.

## CI/CD

There are two candidates: CodeBuild for AWS stack and Jenkins for bare metal.
