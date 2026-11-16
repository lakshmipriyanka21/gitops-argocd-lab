# GitOps Deployment Using Argo CD

## Project Overview
Automated deployment of a Node.js application
to Kubernetes using GitHub and Argo CD.

## Technologies Used
- Git and GitHub
- Docker and Docker Hub
- Kubernetes
- Argo CD
- Node.js
- Killercoda Kubernetes Playground

## Architecture
Developer -> GitHub -> Argo CD -> Kubernetes
                                    |
                              Node.js Pods

## Project Structure
- app/ : Node.js application
- Dockerfile : Container image definition
- k8s/ : Kubernetes manifests
- argocd/ : Argo CD application manifest

## Implementation
1. Created Node.js application.
2. Built Docker image.
3. Pushed image to Docker Hub.
4. Created Kubernetes Deployment and Service.
5. Pushed manifests to GitHub.
6. Installed Argo CD.
7. Configured automated synchronization.
8. Tested self-healing.
9. Updated replicas from 1 to 2 in GitHub.
10. Verified automatic deployment.

## Final Results
- Argo CD Sync: Synced
- Application Health: Healthy
- Deployment: 2/2 Ready
- Running Pods: 2
- Git Auto Sync: Successful

## GitHub Repository
https://github.com/lakshmipriyanka21/gitops-argocd-lab

## Docker Hub
https://hub.docker.com/r/lakshmipriya1234/gitops-node-app

## Conclusion
Successfully implemented GitOps-based
continuous deployment using Argo CD
and Kubernetes.
