# Alfresco Digital Business Platform Prerequisites

The Alfresco Digital Business Platform Deployment requires:

| Component   | Recommended version | Getting Started Guide |
| ------------|:-----------: | ---------------------- |
| Docker      | 19.03.1      | https://docs.docker.com/ |
| Kubernetes  | 1.14.7       | https://kubernetes.io/docs/tutorials/kubernetes-basics/ |
| Kubectl     | 1.14.7       | https://kubernetes.io/docs/tasks/tools/install-kubectl/ |
| Helm        | 2.14.3       | https://docs.helm.sh/using_helm/#quickstart-guide |

In addition, since it can be deployed to different environments, check the requirements for:
- [KOPS deployment](#KOPS)
- [EKS deployment](#EKS)
- [Docker Desktop deployment](#Docker-Desktop)

# KOPS
For KOPS deployment you will also need:

| Component   | Recommended version | Getting Started Guide |
| ------------|:-----------: | ---------------------- |
| Kops        | 1.8.1        | https://github.com/kubernetes/kops/blob/master/docs/aws.md |

# EKS
For EKS deployment you will also need:

| Component   | Recommended version | Getting Started Guide |
| ------------|:-----------: | ---------------------- |
| AWS Cli     | 1.16.33      | https://github.com/aws/aws-cli#installation |

# Docker Desktop
For Docker Desktop deployment you will also need:

| Component          | Recommended version | Getting Started Guide |
| -------------------| :--------------: | ----------------------   |
| Homebrew           |  1.7.7           | https://brew.sh/         |
| Docker Desktop     |  2.0.0.0         | https://www.docker.com/products/docker-desktop |

Any variation from these technologies and versions may affect the end result. 
