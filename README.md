# Backend CI/CD Pipeline - End to End Implementation on EKS

This project demonstrates a robust end-to-end CI/CD pipeline for deploying a backend application on AWS EKS (Elastic Kubernetes Service) with complete DevSecOps and GitOps practices.

### In this demo, we will see how to deploy an end to end backend application on EKS cluster.

### <mark>Project Deployment Flow:</mark>

<img src="https://github.com/ronaks9065/devsecops-pipeline/blob/master/automations/DevSecOps%2BGitOps.gif" />

## Tech stack used in this project:
- GitHub (Code)
- Docker (Containerization)
- Jenkins (CI)
- OWASP (Dependency check)
- SonarQube (Quality)
- Trivy (Filesystem Scan)
- ArgoCD (CD)
- Redis (Caching)
- AWS EKS (Kubernetes)

# Best Practices Implemented
- Shift Left Security Approach: Integrating security checks (OWASP and Trivy) early in the CI process.
- Immutable Docker Image: Docker build and push with unique tags for every CI pipeline run.
- Code Quality Gate: SonarQube for static code analysis and enforcing quality thresholds.
- GitOps with ArgoCD: Declarative deployment and automatic synchronization of Kubernetes resources.
- Scalability & Resilience: Deployment on AWS EKS with auto-scaling and high availability.

# Advantages of This CI/CD Pipeline
- Improved Security: Vulnerability scanning at both the code and container levels.
- Faster Feedback Loop: Automated code quality analysis and security checks.
- Zero Downtime Deployment: ArgoCD ensures seamless Kubernetes deployments.

# Benefits of GitOps with ArgoCD
- No manual kubectl commands.
- Continuous synchronization with the GitHub repo.
- Rollback to previous versions with ease.

# Conclusion
- This CI/CD pipeline is a complete DevSecOps solution with best practices for security, code quality, containerization, and GitOps-driven continuous deployment.

