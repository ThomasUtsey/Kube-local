# Kubernetes Learning Exercises

A progressive learning path for mastering Kubernetes concepts and practices with hands-on exercises and interactive Jupyter notebooks.

## Quick Start

1. **Setup Environment**: Start with `00-setup/kubernetes-setup.ipynb` for complete installation guide
2. **Begin Learning**: Progress through exercises from beginner to expert level
3. **Interactive Demos**: Use Jupyter notebooks for guided demonstrations
4. **Practice**: Apply YAML configurations with kubectl commands

## Learning Path Structure

### 00-Setup
- Environment setup guide
- Podman installation (Mac, Linux, Windows)
- VS Code Kubernetes extension
- kubectl CLI installation
- Minikube cluster setup
- Development environment verification

### 01-Beginner
- Basic Pod concepts
- Deployments and ReplicaSets
- Services and networking basics
- ConfigMaps and Secrets
- Basic troubleshooting
- Namespaces
- Container to container communication within a pod

### 02-Intermediate
- Persistent Volumes and Claims
- StatefulSets and DaemonSets
- Ingress controllers
- Resource management
- Health checks and probes
- Pod to pod communication
- Jobs

### 03-Advanced
- Custom Resource Definitions (CRDs)
- Operators and controllers
- Network policies
- RBAC and security
- CronJobs

### 04-Expert
- Advanced scheduling and communication patterns
- Complex job patterns with automation
- Multi-cluster management
- Service mesh integration
- Advanced monitoring
- GitOps workflows
- Performance optimization

## Getting Started

### Option 1: Interactive Notebooks (Recommended)
1. **Setup**: Run `00-setup/kubernetes-setup.ipynb` to install all prerequisites
2. **Learn**: Open the appropriate level notebook:
   - `01-beginner/kubernetes-beginner-demo.ipynb`
   - `02-intermediate/kubernetes-intermediate-demo.ipynb`
   - `03-advanced/kubernetes-advanced-demo.ipynb`
   - `04-expert/kubernetes-expert-demo.ipynb`
3. **Execute**: Run cells step-by-step with explanations and expected outputs

### Option 2: Manual Exercises
1. Start with `01-beginner/` YAML files
2. Apply configurations using `kubectl apply -f <filename>`
3. Verify results with `kubectl get` commands
4. Progress through each level systematically

## Features

- **📚 Progressive Learning**: Structured path from basics to expert level
- **🔧 Interactive Notebooks**: Jupyter notebooks with live demonstrations
- **💡 Detailed Explanations**: "Why this matters" sections for each concept
- **📝 Commented YAML**: Inline explanations of configuration options
- **🖥️ Multi-Platform**: Setup instructions for Mac, Linux, and Windows
- **🎯 Practical Examples**: Real-world scenarios and use cases
- **🔍 Expected Outputs**: Sample results for verification

## Prerequisites

- **Required**: Computer with 4GB+ RAM and internet connection
- **Installed via setup notebook**:
  - Podman container engine
  - kubectl CLI tool
  - Minikube local cluster
  - VS Code with Kubernetes extension
- **Helpful**: Basic understanding of containers and command line

## Repository Structure

```
minikube/
├── 00-setup/                    # Environment setup
│   └── kubernetes-setup.ipynb   # Complete installation guide
├── 01-beginner/                 # Basic concepts
│   ├── *.yaml                   # Exercise configurations
│   └── kubernetes-beginner-demo.ipynb
├── 02-intermediate/             # Advanced workloads
│   ├── *.yaml
│   └── kubernetes-intermediate-demo.ipynb
├── 03-advanced/                 # Security & networking
│   ├── *.yaml
│   └── kubernetes-advanced-demo.ipynb
├── 04-expert/                   # Enterprise patterns
│   ├── *.yaml
│   └── kubernetes-expert-demo.ipynb
└── README.md                    # This file
```

## Support

- **Troubleshooting**: Check the setup notebook for common issues
- **Expected Outputs**: Each notebook shows sample results
- **Progressive Difficulty**: Master each level before advancing