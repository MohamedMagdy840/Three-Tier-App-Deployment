# Three-Tier-App-Deployment

## Prerequisites

### AWS Account
**Details:** Ensure you have an AWS account set up with access to ECR and EKS services. You'll need the AWS CLI installed and configured with your AWS credentials.

### Kubernetes Cluster
**Details:** Set up a Kubernetes cluster using EKS. Ensure kubectl is configured to interact with your EKS cluster.

### Jenkins Server
**Details:** Set up Jenkins with the necessary plugins:
- **Docker Plugin:** For building Docker images.
- **Kubernetes Plugin:** For deploying to Kubernetes.
- **AWS ECR Plugin:** For pushing images to ECR.
- **GitHub Plugin:** For triggering builds from GitHub.

## Setup Instructions

### 1. Clone the Repository
**Purpose:** Retrieve the project files.

**Details:** Use git clone to download the repository and navigate into the project directory.

```bash
git clone https://github.com/yourusername/three-tier-app.git
cd three-tier-app

