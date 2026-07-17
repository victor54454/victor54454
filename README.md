## Victor Mercier

**Platform / SRE**  
J'opère un parc Kubernetes multi-cloud (OVH, Scaleway), multi-région et multi-master chez RepairSoft. Accès infra via Teleport, déploiements GitOps avec ArgoCD, CI/CD GitHub Actions.

📍 Montpellier · M2 Architecture Systèmes, Réseaux & Sécurité

---

### Stack

**Orchestration** Kubernetes (kubeadm, multi-master, HPA/VPA, Calico) · Helm · ArgoCD  
**Accès & sécurité** Teleport · Istio (mTLS) · SOPS/Age · Vault · Falco · KubeArmor · Trivy  
**CI/CD** GitHub Actions (self-hosted runners) · GitOps  
**Cloud & réseau** OVH · Scaleway · HAProxy (HA, ACL routing) · Nginx · cert-manager  
**Dev & data** Python (Flask) · PostgreSQL · Redis · Bash · Symfony/PHP  

---

### Projets

**[POC-SOPS-ARGOCD](https://github.com/victor54454/POC-SOPS-ARGOCD)**  
Secret management GitOps. Déchiffrement SOPS/Age à la volée via un CMP sidecar custom. Secrets chiffrés en Git, aucun secret en clair dans l'API ArgoCD.

**[POC-VAULT-ARGOCD](https://github.com/victor54454/POC-VAULT-ARGOCD)**  
Même problématique traitée avec Vault self-hosted + Vault Secrets Operator et auth Kubernetes. Comparaison des deux approches documentée.

**[bitwarden_helm](https://github.com/victor54454/bitwarden_helm)**  
Bitwarden self-hosted sur K8s. Helm + ingress-nginx, backup MSSQL chiffré GPG vers S3 OVH, procédure de restauration testée.

**Argos** *(bientôt public)*  
Monitoring multi-cluster Kubernetes. Flask + PostgreSQL, scaling horizontal, health scoring, alerting Discord/mail, éditeur YAML intégré.

---

### Autres

- **[Hackathon H-Secure](https://github.com/victor54454/Gr8-HACKATON-2026)** : chef de projet, équipe de 4, 2e place sur 10 (sécurisation d'un SI de clinique)
- **[Mahoni_V2](https://github.com/victor54454/Mahoni_V2)** : site vitrine + prise de RDV pour coach VTT indépendant, en production depuis décembre 2025

---

### Contact

[LinkedIn](https://www.linkedin.com/in/victor-mercier-232842311) · questmk320@tuta.io