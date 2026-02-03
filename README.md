# Useful Resources

This repository is simply a list of websites, articles, and projects I regularly use, for my reference. 

---

## Security foundations & standards

-  **OWASP** - Open Web Application Security Project
  [https://owasp.org/](https://owasp.org/)

-  **NIST SP 800-190** - Application Container Security Guide
  [https://csrc.nist.gov/publications/detail/sp/800-190/final](https://csrc.nist.gov/publications/detail/sp/800-190/final)

-  **Most Common OpenSSL Commands** - SSL Shopper
  [https://www.sslshopper.com/article-most-common-openssl-commands.html](https://www.sslshopper.com/article-most-common-openssl-commands.html)

---

## Container security & runtime internals

-  **Container Security Checklist** (krol3)
  [https://github.com/krol3/container-security-checklist](https://github.com/krol3/container-security-checklist)

### Frequently used links from the Container Security Checklist

(These all appear on the Container Security Checklist; listed here because I reference them often.)

-  **Trivy** - Vulnerability scanning ? (2023)
  [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy)

-  **runc** - OCI runtime implementation
  [https://github.com/opencontainers/runc](https://github.com/opencontainers/runc)

-  **containerd** - Industry-standard container runtime
  [https://containerd.io/](https://containerd.io/)

-  **Docker Bench for Security** - CIS Docker benchmark automation
  [https://github.com/docker/docker-bench-security](https://github.com/docker/docker-bench-security)

-  **cosign** - Container signing, verification, and transparency
  [https://github.com/sigstore/cosign](https://github.com/sigstore/cosign)

-  **7 Best Practices for Building Containers** - Google Cloud Blog
  [https://cloud.google.com/blog/products/containers-kubernetes/7-best-practices-for-building-containers](https://cloud.google.com/blog/products/containers-kubernetes/7-best-practices-for-building-containers)

-  **Docker Image Tags: Best Practices** - Aqua Security Blog
  [https://blog.aquasec.com/docker-image-tags](https://blog.aquasec.com/docker-image-tags)

-  **Container Vulnerability Scanning Fun** - Raesene Blog
  [https://raesene.github.io/blog/2020/06/21/Container_Vulnerability_Scanning_Fun/](https://raesene.github.io/blog/2020/06/21/Container_Vulnerability_Scanning_Fun/)

-  **Amazon ECR Security Best Practices** - AWS Documentation
  [https://docs.aws.amazon.com/AmazonECR/latest/userguide/security.html](https://docs.aws.amazon.com/AmazonECR/latest/userguide/security.html)

-  **DevSecOps with Trivy and GitHub Actions** - Aqua Security Blog
  [https://blog.aquasec.com/devsecops-with-trivy-github-actions](https://blog.aquasec.com/devsecops-with-trivy-github-actions)

### Debugging Kubernetes security issues

-  **Kubernetes Security Best Practices** - Official documentation
  [https://kubernetes.io/docs/concepts/security/](https://kubernetes.io/docs/concepts/security/)

-  **kube-bench** - CIS Kubernetes Benchmark checks
  [https://github.com/aquasecurity/kube-bench](https://github.com/aquasecurity/kube-bench)

-  **Falco** - Runtime security and syscall detection (CNCF)
  [https://falco.org/](https://falco.org/)

---

## Cloud platforms & tooling documentation

### Cloud provider consoles

-  **AWS Management Console**
  [https://console.aws.amazon.com/](https://console.aws.amazon.com/)

-  **Google Cloud Console**
  [https://console.cloud.google.com/](https://console.cloud.google.com/)

-  **Microsoft Azure Portal**
  [https://portal.azure.com/](https://portal.azure.com/)

### Cloud provider documentation

-  **AWS Documentation**
  [https://docs.aws.amazon.com/](https://docs.aws.amazon.com/)

-  **Google Cloud Documentation**
  [https://cloud.google.com/docs](https://cloud.google.com/docs)

-  **Microsoft Azure Documentation**
  [https://learn.microsoft.com/azure](https://learn.microsoft.com/azure)

### Managed orchestration comparisons

-  **Amazon ECS** - Container orchestration service ✓ (2025)
  [https://aws.amazon.com/ecs/](https://aws.amazon.com/ecs/)

-  **Amazon EKS** - Managed Kubernetes service ✓ (2025)
  [https://aws.amazon.com/eks/](https://aws.amazon.com/eks/)

-  **Choosing Between Amazon EKS, ECS, and Fargate** - AWS Blog
  [https://aws.amazon.com/blogs/containers/choosing-between-amazon-eks-amazon-ecs-and-aws-fargate/](https://aws.amazon.com/blogs/containers/choosing-between-amazon-eks-amazon-ecs-and-aws-fargate/)

### Infrastructure tooling documentation

-  **Splunk Documentation** ✓ (2018)
  [https://help.splunk.com/en](https://help.splunk.com/en)

-  **AWS Provider for Terraform** - Official provider documentation ✓ (2025)
  [https://registry.terraform.io/providers/hashicorp/aws/latest/docs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)

-  **Nebula** - Secure overlay networking documentation
  [https://nebula.defined.net/docs/](https://nebula.defined.net/docs/)

---

## Cloud security

### Vendor-neutral guidance and frameworks

-  **CISA Cloud Security Technical Reference Architecture (TRA)**
  [https://www.cisa.gov/resources-tools/resources/cloud-security-technical-reference-architecture](https://www.cisa.gov/resources-tools/resources/cloud-security-technical-reference-architecture)

-  **MITRE ATT&CK for Cloud** - Adversary techniques in cloud environments
  [https://attack.mitre.org/matrices/enterprise/cloud/](https://attack.mitre.org/matrices/enterprise/cloud/)

-  **OWASP Top 10 for Cloud-Native Applications**
  [https://owasp.org/www-project-cloud-native-top-10/](https://owasp.org/www-project-cloud-native-top-10/)

-  **NIST SP 800-53** - Security and privacy controls
  [https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)

### Cloud and container security tooling (vendor)

-  **Wiz** - Cloud security posture management (CSPM) ✓ (2025)
  [https://www.wiz.io/](https://www.wiz.io/)

-  **Sysdig** - Container and runtime security ? (2023)
  [https://sysdig.com/](https://sysdig.com/)

-  **Aqua Security** - Container and cloud-native security ? (2023)
  [https://www.aquasec.com/](https://www.aquasec.com/)

## SIEMs and security analytics

- **Splunk** - SIEM and security analytics platform ✓ (2018)\
  https://www.splunk.com/

- **Google SecOps (Chronicle)** - Cloud-native SIEM ✓ (2025)\
  https://cloud.google.com/security/products/chronicle

- **Microsoft Sentinel** - Cloud-native SIEM ✓ (2025)\
  https://learn.microsoft.com/azure/sentinel/

- **Securonix** - User and entity behavior analytics (UEBA) SIEM ✓ (2022)\
  https://www.securonix.com/

- **Datadog SIEM** - Cloud-native SIEM and security monitoring ? (2024)\
  https://www.datadoghq.com/product/siem/

- **Elastic Security** - SIEM built on the Elastic Stack\
  https://www.elastic.co/security

---

## Reliability, operations, and engineering culture

-  **SRE Doesn't Scale** - Brave New Geek
  [https://bravenewgeek.com/sre-doesnt-scale/](https://bravenewgeek.com/sre-doesnt-scale/)

-  **Linux Performance** - Brendan Gregg (outdated but still useful)
  [https://www.brendangregg.com/linuxperf.html](https://www.brendangregg.com/linuxperf.html)

-  **Programming Tech That Ages Well vs Tools That Rot Fast** - Medium
  [https://medium.com/stackademic/programming-tech-that-ages-well-versus-tools-that-rot-fast-aa4649511d46](https://medium.com/stackademic/programming-tech-that-ages-well-versus-tools-that-rot-fast-aa4649511d46)

### Debugging Kubernetes performance and reliability

-  **Kubernetes Debugging Guide** - Official troubleshooting docs
  [https://kubernetes.io/docs/tasks/debug/](https://kubernetes.io/docs/tasks/debug/)

-  **USE Method** - Brendan Gregg
  [https://www.brendangregg.com/usemethod.html](https://www.brendangregg.com/usemethod.html)

-  **Kube-burner** - Performance and scale testing for Kubernetes
  [https://github.com/kube-burner/kube-burner](https://github.com/kube-burner/kube-burner)

---

## Reference, perspective, and occasional sanity checks

-  **Is It Worth the Time?*# Frequently Reviewed Resources

This repository is simply a curated list of websites, articles, and projects I regularly revisit. There is no deeper structure or intent beyond keeping useful references in one place so I do not lose track of them.

Links come and go over time; this is a living list.

---

## Security foundations & standards

-  **OWASP** - Open Web Application Security Project
  [https://owasp.org/](https://owasp.org/)

-  **NIST SP 800-190** - Application Container Security Guide
  [https://csrc.nist.gov/publications/detail/sp/800-190/final](https://csrc.nist.gov/publications/detail/sp/800-190/final)

-  **Most Common OpenSSL Commands** - SSL Shopper
  [https://www.sslshopper.com/article-most-common-openssl-commands.html](https://www.sslshopper.com/article-most-common-openssl-commands.html)

---

## Container security & runtime internals

-  **Container Security Checklist** (krol3)
  [https://github.com/krol3/container-security-checklist](https://github.com/krol3/container-security-checklist)

### Frequently used links from the Container Security Checklist

(These all appear on the Container Security Checklist; listed here because I reference them often.)

-  **Trivy** - Vulnerability scanning ? (2023)
  [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy)

-  **runc** - OCI runtime implementation
  [https://github.com/opencontainers/runc](https://github.com/opencontainers/runc)

-  **containerd** - Industry-standard container runtime
  [https://containerd.io/](https://containerd.io/)

-  **Docker Bench for Security** - CIS Docker benchmark automation
  [https://github.com/docker/docker-bench-security](https://github.com/docker/docker-bench-security)

-  **cosign** - Container signing, verification, and transparency ? (2025)
  [https://github.com/sigstore/cosign](https://github.com/sigstore/cosign)

-  **7 Best Practices for Building Containers** - Google Cloud Blog
  [https://cloud.google.com/blog/products/containers-kubernetes/7-best-practices-for-building-containers](https://cloud.google.com/blog/products/containers-kubernetes/7-best-practices-for-building-containers)

-  **Docker Image Tags: Best Practices** - Aqua Security Blog
  [https://blog.aquasec.com/docker-image-tags](https://blog.aquasec.com/docker-image-tags)

-  **Container Vulnerability Scanning Fun** - Raesene Blog
  [https://raesene.github.io/blog/2020/06/21/Container_Vulnerability_Scanning_Fun/](https://raesene.github.io/blog/2020/06/21/Container_Vulnerability_Scanning_Fun/)

-  **Amazon ECR Security Best Practices** - AWS Documentation
  [https://docs.aws.amazon.com/AmazonECR/latest/userguide/security.html](https://docs.aws.amazon.com/AmazonECR/latest/userguide/security.html)

-  **DevSecOps with Trivy and GitHub Actions** - Aqua Security Blog
  [https://blog.aquasec.com/devsecops-with-trivy-github-actions](https://blog.aquasec.com/devsecops-with-trivy-github-actions)

### Debugging Kubernetes security issues

-  **Kubernetes Security Best Practices** - Official documentation
  [https://kubernetes.io/docs/concepts/security/](https://kubernetes.io/docs/concepts/security/)

-  **kube-bench** - CIS Kubernetes Benchmark checks
  [https://github.com/aquasecurity/kube-bench](https://github.com/aquasecurity/kube-bench)

-  **Falco** - Runtime security and syscall detection (CNCF)
  [https://falco.org/](https://falco.org/)

---

## Cloud platforms & tooling documentation

### Cloud provider consoles

-  **AWS Management Console**
  [https://console.aws.amazon.com/](https://console.aws.amazon.com/)

-  **Google Cloud Console**
  [https://console.cloud.google.com/](https://console.cloud.google.com/)

-  **Microsoft Azure Portal**
  [https://portal.azure.com/](https://portal.azure.com/)

### Cloud provider documentation

-  **AWS Documentation**
  [https://docs.aws.amazon.com/](https://docs.aws.amazon.com/)

-  **Google Cloud Documentation**
  [https://cloud.google.com/docs](https://cloud.google.com/docs)

-  **Microsoft Azure Documentation**
  [https://learn.microsoft.com/azure](https://learn.microsoft.com/azure)

### Managed orchestration comparisons

-  **Amazon ECS** - Container orchestration service ✓ (2025)
  [https://aws.amazon.com/ecs/](https://aws.amazon.com/ecs/)

-  **Amazon EKS** - Managed Kubernetes service ✓ (2025)
  [https://aws.amazon.com/eks/](https://aws.amazon.com/eks/)

-  **Choosing Between Amazon EKS, ECS, and Fargate** - AWS Blog
  [https://aws.amazon.com/blogs/containers/choosing-between-amazon-eks-amazon-ecs-and-aws-fargate/](https://aws.amazon.com/blogs/containers/choosing-between-amazon-eks-amazon-ecs-and-aws-fargate/)

### Infrastructure tooling documentation

-  **Splunk Documentation** ✓ (2025)
  [https://help.splunk.com/en](https://help.splunk.com/en)

-  **AWS Provider for Terraform** - Official provider documentation ✓ (2025)
  [https://registry.terraform.io/providers/hashicorp/aws/latest/docs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)

-  **Nebula** - Secure overlay networking documentation
  [https://nebula.defined.net/docs/](https://nebula.defined.net/docs/)

---

## Cloud security

### Vendor-neutral guidance and frameworks

-  **CISA Cloud Security Technical Reference Architecture (TRA)**
  [https://www.cisa.gov/resources-tools/resources/cloud-security-technical-reference-architecture](https://www.cisa.gov/resources-tools/resources/cloud-security-technical-reference-architecture)

-  **MITRE ATT&CK for Cloud** - Adversary techniques in cloud environments
  [https://attack.mitre.org/matrices/enterprise/cloud/](https://attack.mitre.org/matrices/enterprise/cloud/)

-  **OWASP Top 10 for Cloud-Native Applications**
  [https://owasp.org/www-project-cloud-native-top-10/](https://owasp.org/www-project-cloud-native-top-10/)

-  **NIST SP 800-53** - Security and privacy controls
  [https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)

### Cloud and container security tooling (vendor)

-  **Wiz** - Cloud security posture management (CSPM) ✓ (2025)
  [https://www.wiz.io/](https://www.wiz.io/)

-  **Sysdig** - Container and runtime security ? (2023)
  [https://sysdig.com/](https://sysdig.com/)

-  **Aqua Security** - Container and cloud-native security ? (2023)
  [https://www.aquasec.com/](https://www.aquasec.com/)

---

## Reliability, operations, and engineering culture

-  **SRE Doesn’t Scale** - Brave New Geek
  [https://bravenewgeek.com/sre-doesnt-scale/](https://bravenewgeek.com/sre-doesnt-scale/)

-  **Linux Performance** - Brendan Gregg (outdated but still useful)
  [https://www.brendangregg.com/linuxperf.html](https://www.brendangregg.com/linuxperf.html)

-  **Programming Tech That Ages Well vs Tools That Rot Fast** - Medium
  [https://medium.com/stackademic/programming-tech-that-ages-well-versus-tools-that-rot-fast-aa4649511d46](https://medium.com/stackademic/programming-tech-that-ages-well-versus-tools-that-rot-fast-aa4649511d46)

### Debugging Kubernetes performance and reliability

-  **Kubernetes Debugging Guide** - Official troubleshooting docs
  [https://kubernetes.io/docs/tasks/debug/](https://kubernetes.io/docs/tasks/debug/)

-  **USE Method** - Brendan Gregg
  [https://www.brendangregg.com/usemethod.html](https://www.brendangregg.com/usemethod.html)

-  **Kube-burner** - Performance and scale testing for Kubernetes
  [https://github.com/kube-burner/kube-burner](https://github.com/kube-burner/kube-burner)

---

## Kubernetes, platform, and systems

-  **I Wish Someone Explained Kubernetes Like This on Day One** - Conceptual Kubernetes primer
  [https://medium.com/@kanishks772/i-wish-someone-explained-kubernetes-like-this-on-day-one-7ca9c470d327](https://medium.com/@kanishks772/i-wish-someone-explained-kubernetes-like-this-on-day-one-7ca9c470d327)

### Kubernetes and orchestration fundamentals

-  **Kubernetes Documentation** - Core concepts and architecture
  [https://kubernetes.io/docs/home/](https://kubernetes.io/docs/home/)

-  **CNCF Landscape** - Cloud-native project ecosystem
  [https://landscape.cncf.io/](https://landscape.cncf.io/)

-  **Kubernetes SIG Security** - Design docs and security direction
  [https://github.com/kubernetes/community/tree/master/sig-security](https://github.com/kubernetes/community/tree/master/sig-security)

---

## AI tooling and applied productivity

-  **NVIDIA DGX Platform** - Integrated systems for AI training and inference
  [https://www.nvidia.com/en-us/data-center/dgx-platform/](https://www.nvidia.com/en-us/data-center/dgx-platform/)

-  **The 15 AI Tools Every Business Will Regret Not Using in 2026** - Applied AI landscape overview
  [https://pub.aimind.so/the-15-ai-tools-every-business-will-regret-not-using-in-2026-5326d42ee65e](https://pub.aimind.so/the-15-ai-tools-every-business-will-regret-not-using-in-2026-5326d42ee65e)

---

## Cloud identity and access

### Identity concepts and architecture

-  **NIST SP 800-63** - Digital identity guidelines
  [https://pages.nist.gov/800-63-3/](https://pages.nist.gov/800-63-3/)

-  **Zero Trust Architecture** - NIST SP 800-207
  [https://csrc.nist.gov/publications/detail/sp/800-207/final](https://csrc.nist.gov/publications/detail/sp/800-207/final)

-  **Identity Is the New Perimeter** - Google BeyondCorp
  [https://cloud.google.com/beyondcorp](https://cloud.google.com/beyondcorp)

### Identity platforms and leaders

-  **Okta** - Workforce identity and access management ✓ (2025)
  [https://www.okta.com/](https://www.okta.com/)

-  **Entra ID (Azure AD)** - Microsoft identity platform ✓ (2025)
  [https://learn.microsoft.com/entra/identity/](https://learn.microsoft.com/entra/identity/)

-  **AWS IAM** - Cloud-native identity and access control ✓ (2025)
  [https://docs.aws.amazon.com/iam/](https://docs.aws.amazon.com/iam/)

---

## Infrastructure as code

-  **A Comprehensive Guide to Terraform** - Gruntwork
  [https://www.gruntwork.io/blog/a-comprehensive-guide-to-terraform](https://www.gruntwork.io/blog/a-comprehensive-guide-to-terraform)

-  **Terragrunt Documentation** - Gruntwork
  [https://terragrunt.gruntwork.io/](https://terragrunt.gruntwork.io/)

-  **Terratest Documentation** - Infrastructure testing framework
  [https://terratest.gruntwork.io/](https://terratest.gruntwork.io/)

  ## Programming languages

### Python

- **Python Documentation** - Official language reference\
  https://docs.python.org/3/

- **boto3** - AWS SDK for Python\
  https://boto3.amazonaws.com/v1/documentation/api/latest/index.html

- **botocore** - Low-level AWS service clients and request signing\
  https://botocore.amazonaws.com/v1/documentation/api/latest/index.html

- **Using Python for Cloud Security Automation** - SANS blog\
  https://www.sans.org/blog/using-python-for-cloud-security-automation/

- **Automating Cloud Security with Python** - AWS Security Blog\
  https://aws.amazon.com/blogs/security/automating-aws-security-checks-with-python/

---

### Bash

- **GNU Bash Reference Manual** - Official documentation\
  https://www.gnu.org/software/bash/manual/bash.html

- **Advanced Bash-Scripting Guide** - TLDP (older, still useful)\
  https://tldp.org/LDP/abs/html/

---

### Node.js

- **Node.js** - JavaScript runtime\
  https://nodejs.org/en

- **Node.js Getting Started** - Official tutorial\
  https://nodejs.org/en/docs/guides/getting-started-guide/

---

### TypeScript

- **TypeScript** - Typed superset of JavaScript\
  https://www.typescriptlang.org/

- **TypeScript Handbook** - Official guide\
  https://www.typescriptlang.org/docs/handbook/intro.html

---

### Go

- **The Go Programming Language** - Official site and docs\
  https://go.dev/

- **A Tour of Go** - Interactive introduction\
  https://go.dev/tour/

---

### Rust

- **Rust Programming Language** - Official site and documentation\
  https://www.rust-lang.org/

- **The Rust Programming Language (The Book)** - Official tutorial\
  https://doc.rust-lang.org/book/

---

## Perspective

-  **Is It Worth the Time?** - xkcd #1205
  [https://xkcd.com/1205/](https://xkcd.com/1205/)

-  **Password Strength** - xkcd #936
  [https://xkcd.com/936/](https://xkcd.com/936/)

---

## Notes

If you happened to stumble across this repository and see something worth commenting on, suggestions and feedback are welcome. The bar here is usefulness, not completeness or polish.

---
Content licensed under CC BY-NC 4.0.
