CrftInfrai
Cloud infrastructure generation, Terraform templates, cloud and LLM cost intelligence, and governed Kubernetes operations.

CrftInfrai helps engineering teams design infrastructure, understand costs before deployment, generate Terraform, and operate Kubernetes with AI-assisted workflows.

Explore CrftInfrai · Open Console · Browse Open Source
Find Your Starting Point
What you want to do	Start here
Design cloud infrastructure and generate Terraform	Cloud Infrastructure Builder
Compare infrastructure costs across cloud providers	Cloud Cost Comparison
Compare LLM pricing and estimate AI workload costs	AI Cost Intelligence
Explore AI-assisted Kubernetes operations	Operations Console
Use public Terraform modules and architecture templates	crftinfrai-infra


Some hosted workflows require sign-in.
What We Build
Cloud Infrastructure Generator
Design infrastructure visually, configure resources, estimate costs, and generate Terraform for review. Start with an architecture template or build your own design across AWS, Azure, Google Cloud, and OCI.

Explore the Infrastructure Builder
Cloud Cost Comparison
Compare infrastructure options across providers using workload requirements such as CPU, memory, storage, and region. Review cost estimates before choosing a deployment configuration.

Compare Cloud Costs
LLM Cost Calculator and AI Cost Intelligence
Compare model pricing and estimate AI workload spend. Explore cost per task, cost per successful task, and Human vs AI economics to understand how usage and outcomes affect cost.

Explore AI Cost Tools
Kubernetes and AgenticOps
Support Kubernetes diagnosis and remediation planning with evidence, human approvals, GitOps changes, and recovery verification.

Explore Kubernetes Operations · View Platform Capabilities
Open Source: Terraform Modules and Architecture Templates
Our public crftinfrai-infra repository contains reusable infrastructure code for AWS, Azure, Google Cloud, and OCI.
Resource	What you will find
Terraform modules	Building blocks for compute, networking, containers, Kubernetes, databases, and storage
Architecture templates	Versioned Terraform root configurations for application and platform foundations
Kubernetes starters	AKS, GKE, and OKE starting architectures with security-focused defaults
Examples	Example configurations and a bootstrap root
Documentation	Repository guidance and links to module and template instructions


You can use the public infrastructure code without a CrftInfrai account. Cloud deployment requires appropriate credentials and can incur provider charges.

The hosted builders, cost intelligence tools, and Kubernetes operations services are separate platform capabilities. Their application source code is not included in crftinfrai-infra.
Explore an Architecture
Architecture	Cloud	Browse the code
EKS + PostgreSQL RDS + Argo CD	AWS	Terraform template
AKS + PostgreSQL + Monitoring	Azure	Terraform template
GKE + Cloud SQL + Argo CD	Google Cloud	Terraform template
Cloud Run + Cloud SQL PostgreSQL	Google Cloud	Terraform template
Fargate Microservices	AWS	Terraform template
OKE Network and Node Pool Foundation	OCI	Kubernetes starter
Lightweight EC2 Development Environment	AWS	Terraform template


Review each project's prerequisites, supported versions, security settings, costs, and cleanup instructions before deployment. Adapt templates to your production requirements.
Clouds and Technologies
Area	Coverage
Cloud providers	AWS, Microsoft Azure, Google Cloud, Oracle Cloud Infrastructure
Managed Kubernetes	Amazon EKS, Azure AKS, Google GKE, OCI OKE
Infrastructure as code	Terraform modules, architecture templates, and generated configurations
Engineering practices	GitOps, platform engineering, DevOps, SRE, and FinOps


Start Building
1. Choose a starting point: open the hosted builder or select a public Terraform template.
2. Configure your architecture: review resource settings, dependencies, and access requirements.
3. Understand costs: compare infrastructure options or estimate AI workload spend.
4. Review and validate: inspect Terraform and its plan before provisioning.
5. Deploy through your workflow: use your team's approval, state management, and operational controls.
Open CrftInfrai Console · Read the Infrastructure Quick Start
Contributing
We welcome bug reports, documentation improvements, practical examples, and ideas for reusable infrastructure patterns.
- Read the contribution guidelines.
- Open an issue or suggest an improvement.
- Review the code of conduct.
- Follow the security policy for vulnerability reports.
Each repository's license governs its published code. See the crftinfrai-infra license.
Connect
Website · Platform Overview · Console · GitHub Projects
