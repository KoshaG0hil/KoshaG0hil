<div align="center">

  <h1>👋 Hi, I'm <span style="color:#6366f1;">Kosha Rajesh Gohil</span></h1>
  
  <p align="center">
    <strong>Cloud & DevSecOps Engineer · Infrastructure Security & SRE Specialist</strong><br/>
    <em>New York, USA</em>
  </p>

  <p align="center">
    <a href="https://linkedin.com/in/koshagohil"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="https://koshag0hil.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
    <a href="mailto:gohilkosha19@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS SAA"/>
    <img src="https://img.shields.io/badge/AWS-Security_Specialty-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS Security"/>
    <img src="https://img.shields.io/badge/CompTIA-Security+-D8232A?style=flat-square&logo=comptia&logoColor=white" alt="CompTIA Security+"/>
    <img src="https://img.shields.io/badge/HashiCorp-Terraform_Associate-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
    <img src="https://img.shields.io/badge/Cisco-CCNA-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="CCNA"/>
  </p>

</div>

---

### 🛡️ About Me

I am a **Cloud Security & DevSecOps Engineer** with 2+ years of hands-on experience designing, hardening, and automating multi-cloud architectures. My work centers on **Zero-Trust infrastructure**, **IAM least-privilege governance**, **Policy-as-Code**, and **automated continuous compliance**.

- 🔭 **Current Focus**: Architecting self-healing infrastructure, Shift-Left DevSecOps gates, Confidential Computing, and AI-accelerated security triage workflows.
- ⚙️ **Production Experience**: Hands-on ownership of production AWS infrastructure, Kubernetes workloads, and observability stacks for a **HIPAA-regulated healthcare platform** (supporting zero-downtime blue/green cutovers for 400-500 daily eRx transactions).
- 🧱 **Security Engineering Mindset**: Replacing fragile manual checklists with codified, auditable security guardrails using **Terraform**, **Open Policy Agent (OPA Rego)**, **Checkov**, **EventBridge**, and **Cloud Run/Lambda**.
- 🎓 **Education & Certifications**: 
  - **M.S. in Computer Science** — Pace University, New York
  - **B.E. in Computer Engineering** — Savitribai Phule Pune University
  - AWS Certified Solutions Architect (Associate) · AWS Certified Security (Specialty) · CompTIA Security+ · HashiCorp Terraform Associate · Cisco CCNA

---

### 💼 What I Bring to an Engineering Team

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🔒 Cloud Security & Governance</h4>
      <p>Automated IAM least-privilege baselines, 14+ privilege escalation signatures, continuous CloudTrail drift detection, CIS AWS Foundations Benchmark compliance, and zero-standing privilege architectures.</p>
    </td>
    <td width="33%" valign="top">
      <h4>🚀 DevSecOps & CI/CD</h4>
      <p>Multi-stage automated pipelines (GitHub Actions, Jenkins) embedding SAST (Bandit), secret leak detection (Gitleaks), container CVE auditing (Trivy), and automated canary rollback controllers with &lt; 2.0s MTTR.</p>
    </td>
    <td width="33%" valign="top">
      <h4>📈 Reliability & Observability (SRE)</h4>
      <p>Production SLI/SLO definitions, error budget governance, multi-AZ high availability, and Prometheus / Grafana / Loki / CloudWatch telemetry reducing incident MTTR by ~40%.</p>
    </td>
  </tr>
</table>

---

### 🛠️ Tech Stack & Capabilities

<table align="center" width="100%">
  <tr>
    <td width="25%" valign="top">
      <h4>☁️ Cloud Platforms</h4>
      <ul>
        <li>AWS (ECS Fargate, Lambda, S3, IAM, CloudTrail, EventBridge, VPC, ALB, WAF, GuardDuty, KMS, RDS, Route 53 ARC)</li>
        <li>Google Cloud (Cloud Run, GCS, Eventarc, Pub/Sub, Firestore)</li>
      </ul>
    </td>
    <td width="25%" valign="top">
      <h4>🔒 Security & Governance</h4>
      <ul>
        <li>IAM Least Privilege & PrivEsc Analysis</li>
        <li>CIS AWS Foundations Benchmarks</li>
        <li>Policy-as-Code (OPA Rego, Checkov)</li>
        <li>Supply Chain Security (SLSA v3, Sigstore)</li>
        <li>Confidential Compute (AWS Nitro Enclaves)</li>
        <li>SAST & Secrets (Bandit, Trivy, Gitleaks)</li>
      </ul>
    </td>
    <td width="25%" valign="top">
      <h4>🚀 DevOps & Containers</h4>
      <ul>
        <li>Terraform (Modular IaC)</li>
        <li>Docker & eBPF Sandboxing</li>
        <li>Kubernetes & Amazon EKS</li>
        <li>GitHub Actions & Automated Rollbacks</li>
        <li>Ansible CIS Server Hardening</li>
      </ul>
    </td>
    <td width="25%" valign="top">
      <h4>💻 Languages & Tooling</h4>
      <ul>
        <li>Python (Boto3, Flask, FastAPI)</li>
        <li>Bash & PowerShell Scripting</li>
        <li>SQL & Query Optimization</li>
        <li>Prometheus, Grafana, Loki, CloudWatch</li>
        <li>Wireshark, VPC Flow Logs, Nmap</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🌟 Flagship Cloud & DevSecOps Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/KoshaG0hil/Zero-Trust-Supply-Chain-eBPF-Sentinel">Zero-Trust Supply Chain eBPF Sentinel</a></h3>
      <p>Kernel-level software supply chain security engine that intercepts build-time container syscalls via Linux eBPF, detects compromised dependencies, emits SLSA Level 3 in-toto cryptographic provenance statements, and enforces Sigstore Cosign keyless admission gates.</p>
      <p>
        <img src="https://img.shields.io/badge/Security-eBPF%20Kernel%20Sandbox-brightgreen?style=flat-square" alt="eBPF"/>
        <img src="https://img.shields.io/badge/Supply_Chain-SLSA%20Level%203-blue?style=flat-square" alt="SLSA"/>
        <img src="https://img.shields.io/badge/Signature-Sigstore%20Cosign-purple?style=flat-square" alt="Cosign"/>
        <img src="https://img.shields.io/badge/Python-3.11+-orange?style=flat-square" alt="Python"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 <a href="https://github.com/KoshaG0hil/AWS-Nitro-Enclave-Confidential-Compute-Vault">Nitro Enclaves Confidential Compute Vault</a></h3>
      <p>Zero-trust hardware memory isolation vault leveraging AWS Nitro Enclaves, cryptographic attestation document parsing (PCR0-2 measurements), AWS KMS <code>RecipientAttestation</code> policy decryption, and clean-room multiparty differential privacy analytics.</p>
      <p>
        <img src="https://img.shields.io/badge/AWS-Nitro%20Enclaves-FF9900?style=flat-square" alt="AWS Nitro"/>
        <img src="https://img.shields.io/badge/Cryptography-COSE%20%2F%20CBOR%20Attestation-blue?style=flat-square" alt="COSE"/>
        <img src="https://img.shields.io/badge/Isolation-KMS%20RecipientAttestation-red?style=flat-square" alt="KMS"/>
        <img src="https://img.shields.io/badge/Privacy-Clean%20Room%20Differential%20Privacy-darkgreen?style=flat-square" alt="Clean Room"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌱 <a href="https://github.com/KoshaG0hil/Carbon-Aware-Autonomous-Cloud-Scheduler">Carbon-Aware Autonomous Cloud Scheduler</a></h3>
      <p>GreenOps optimization scheduler integrating real-time regional electrical grid carbon intensity telemetry (Electricity Maps / WattTime), AWS Spot market cost economics, and Pareto multi-objective optimization to minimize Scope 2 emissions by 30-65%.</p>
      <p>
        <img src="https://img.shields.io/badge/GreenOps-Grid%20Carbon%20Intensity-brightgreen?style=flat-square" alt="GreenOps"/>
        <img src="https://img.shields.io/badge/FinOps-AWS%20Spot%20Economics-orange?style=flat-square" alt="Spot"/>
        <img src="https://img.shields.io/badge/Optimization-Pareto%20Multi--Objective-blue?style=flat-square" alt="Pareto"/>
        <img src="https://img.shields.io/badge/Sustainability-Scope%202%20Emissions-darkgreen?style=flat-square" alt="Emissions"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/KoshaG0hil/Multi-Region-ActiveActive-Disaster-Recovery-Mesh">Multi-Region Active-Active DR Mesh</a></h3>
      <p>Tier-0 enterprise disaster recovery framework on AWS featuring sub-second traffic shifting with Route 53 Application Recovery Controller (ARC), continuous DynamoDB Global Tables replication latency telemetry, and automated chaos blackout fault injection with RTO &lt; 5s and RPO = 0.</p>
      <p>
        <img src="https://img.shields.io/badge/AWS-Route%2053%20ARC-orange?style=flat-square" alt="ARC"/>
        <img src="https://img.shields.io/badge/Storage-DynamoDB%20Global%20Tables-blue?style=flat-square" alt="DynamoDB"/>
        <img src="https://img.shields.io/badge/Reliability-RTO%20%3C%205s%20%7C%20RPO%200ms-brightgreen?style=flat-square" alt="RTO RPO"/>
        <img src="https://img.shields.io/badge/Chaos-Fault%20Injection-red?style=flat-square" alt="Chaos"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/KoshaG0hil/Autonomous-AI-Cloud-RedTeam-Chaos-Agent">Autonomous AI Cloud Red-Team & Chaos Engine</a></h3>
      <p>Agentic AI adversary emulation engine that autonomously synthesizes multi-hop cloud attack graphs, discovers lateral movement paths to crown jewels, scores blast radius, and auto-generates self-healing Terraform code.</p>
      <p>
        <img src="https://img.shields.io/badge/AI_Agent-ReAct%20Loop-red?style=flat-square" alt="AI Agent"/>
        <img src="https://img.shields.io/badge/Graph-NetworkX-blue?style=flat-square" alt="NetworkX"/>
        <img src="https://img.shields.io/badge/MITRE-ATT%26CK%20Cloud-orange?style=flat-square" alt="MITRE ATT&CK"/>
        <img src="https://img.shields.io/badge/IaC-Terraform%20Self--Healing-purple?style=flat-square" alt="Terraform"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚛️ <a href="https://github.com/KoshaG0hil/Post-Quantum-Cloud-Cryptography-Sentinel">Post-Quantum Cloud Cryptography Sentinel</a></h3>
      <p>Automated quantum risk discovery engine evaluating AWS CloudFront, ALB, KMS, and S3 against NIST FIPS 203 (ML-KEM) standards. Computes Quantum Vulnerability Index (QVI) against HNDL attacks and generates hybrid PQC Terraform migrations.</p>
      <p>
        <img src="https://img.shields.io/badge/NIST-FIPS%20203%20ML--KEM-purple?style=flat-square" alt="NIST PQC"/>
        <img src="https://img.shields.io/badge/AWS-KMS%20%7C%20CloudFront%20%7C%20S3-orange?style=flat-square" alt="AWS"/>
        <img src="https://img.shields.io/badge/Threat-HNDL%20Defense-red?style=flat-square" alt="HNDL"/>
        <img src="https://img.shields.io/badge/Security-CNSA%202.0-brightgreen?style=flat-square" alt="CNSA"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/KoshaG0hil/Automated-IAM-Governance-Engine">Automated IAM Governance & Drift Detection</a></h3>
      <p>Continuous IAM governance platform evaluating roles & policies against least-privilege baselines. Features 14+ privilege escalation signatures, compound anomaly scoring, AI triage queue routing, real-time CloudTrail SNS alerts, and interactive audit dashboards.</p>
      <p>
        <img src="https://img.shields.io/badge/AWS-IAM%20%7C%20EventBridge%20%7C%20Lambda-orange?style=flat-square" alt="AWS"/>
        <img src="https://img.shields.io/badge/Python-3.12-blue?style=flat-square" alt="Python"/>
        <img src="https://img.shields.io/badge/Terraform-v1.5+-purple?style=flat-square" alt="Terraform"/>
        <a href="https://koshag0hil.github.io/Automated-IAM-Governance-Engine/"><img src="https://img.shields.io/badge/Live_Demo-Interactive-success?style=flat-square" alt="Live Demo"/></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🚀 <a href="https://github.com/KoshaG0hil/Secure-CICD-Infrastructure-Automation-Pipeline">Secure CI/CD & Rollback Controller</a></h3>
      <p>Enterprise 6-stage DevSecOps pipeline with shift-left source security (Bandit, Gitleaks, pip-audit), OPA Rego IaC validation, Trivy container scanning, approval gates, and automated canary rollbacks restoring health in &lt; 2.0s.</p>
      <p>
        <img src="https://img.shields.io/badge/GitHub_Actions-CI%2FCD-black?style=flat-square" alt="GH Actions"/>
        <img src="https://img.shields.io/badge/AWS-ECS%20Fargate%20%7C%20ALB-orange?style=flat-square" alt="AWS ECS"/>
        <img src="https://img.shields.io/badge/Policy_as_Code-OPA_Rego-brightgreen?style=flat-square" alt="OPA"/>
        <img src="https://img.shields.io/badge/Trivy-Container_Scan-blue?style=flat-square" alt="Trivy"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🦠 <a href="https://github.com/KoshaG0hil/serverless-virus-scanning-system">Serverless Malware Detection Pipeline</a></h3>
      <p>Dual-cloud serverless antivirus pipeline built with <strong>Google Cloud Run</strong> (GCS + Eventarc + ClamAV + Pub/Sub) and <strong>AWS Lambda</strong> (S3 + DynamoDB + SNS). Uses 3-tier zero-trust isolation and automated quarantine.</p>
      <p>
        <img src="https://img.shields.io/badge/Google_Cloud-Cloud_Run%20%7C%20GCS-4285F4?style=flat-square" alt="GCP"/>
        <img src="https://img.shields.io/badge/AWS-Lambda%20%7C%20S3-FF9900?style=flat-square" alt="AWS"/>
        <img src="https://img.shields.io/badge/Antivirus-ClamAV-red?style=flat-square" alt="ClamAV"/>
        <img src="https://img.shields.io/badge/Docker-OCI-2496ED?style=flat-square" alt="Docker"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔒 <a href="https://github.com/KoshaG0hil/Project-2-linux-hardening">Bastionless CIS Linux Hardening</a></h3>
      <p>Automated CIS Benchmark Level 1 & 2 server hardening and zero-bastion architecture using Ansible playbooks, Terraform, and AWS Systems Manager (SSM) Session Manager over private VPC Endpoints.</p>
      <p>
        <img src="https://img.shields.io/badge/Ansible-Hardening-EE0000?style=flat-square" alt="Ansible"/>
        <img src="https://img.shields.io/badge/AWS-SSM%20Endpoints-orange?style=flat-square" alt="AWS SSM"/>
        <img src="https://img.shields.io/badge/Security-CIS_Benchmark-darkgreen?style=flat-square" alt="CIS"/>
        <img src="https://img.shields.io/badge/Terraform-IaC-purple?style=flat-square" alt="Terraform"/>
      </p>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KoshaG0hil&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KoshaG0hil&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</div>

---

<div align="center">
  <sub>Engineered by <strong>Kosha Gohil</strong> · Open to Cloud Security & DevSecOps Engineering Roles</sub>
</div>
