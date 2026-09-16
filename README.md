<div align="center">

# 🛡️ Anne-LaureS 🌺

### ⚡ Cybersecurity & Cloud Computing

<img src="banner.svg" alt="GRC · IAM Governance · Cloud Security · SecOps" />

[![TryHackMe Top 1%](https://img.shields.io/badge/TryHackMe-Top_1%25_🏆-red?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Ann3LAu43)
[![Rooms Solved](https://img.shields.io/badge/THM_Rooms-221_Solved-00b4d8?style=for-the-badge&logo=tryhackme&logoColor=white)](#-tryhackme-achievements)
[![Badges](https://img.shields.io/badge/THM_Badges-41_Badges-purple?style=for-the-badge)](#-tryhackme-achievements)

---

</div>

## 🧬 Operator Profile

```yaml
Operator : "Anne-LaureS"
Status: "En formation — Expertise Cybersécurité & Cloud Computing, 5ème année"
Experience: "5 ans en Cybersécurité, dont 2 ans dédiés à l'IAM"
Career_Path:
- Cheffe de projet Sécurité & Conformité
- Assistante RSSI
- Administratrice SecOps — spécialité macOS
- Attachée Sécurité Informatique — spécialiste IAM (poste actuel)
Focus_Areas:
- IAM & Access Governance
- Cloud Security (AWS · Azure)
- Compliance & Security Project Management
- SecOps
- Infrastructure as Code (Terraform, Ansible, Kubernetes, Jenkins)
Open_To: "Opportunités Cybersécurité — GRC, SecOps, IAM, Cloud Security"
```

---

## 🛠️ Featured Security Projects

### 🧭 [IAM-Governance-Roadmap](https://github.com/Anne-LaureS/IAM-Governance-Roadmap)
> Le volet pilotage du programme IAM ci-dessous : roadmap en phases (Visibilité → Gouvernance →
> Automatisation → Authentification → Pilotage continu), RACI, comité de pilotage, KPIs
> calculables à partir des sorties réelles des scripts — chaque phase reliée au repo technique
> qui la livre concrètement.
>
> `IAM Governance` `Program Management` `RACI` `KPIs` `Mermaid`

### 🔑 [Okta-SSO-Debug-Lab](https://github.com/Anne-LaureS/Okta-SSO-Debug-Lab)
> Procédure de debug SSO de bout en bout contre un tenant Okta réel : une app OIDC
> (`client_credentials`, JWT/JWKS, `private_key_jwt`) et une app SAML 2.0 (assertions,
> bindings, signature XML), avec une collection Bruno qui automatise chaque étape de
> vérification. Le flow OIDC est rejoué automatiquement en CI (GitHub Actions) — le badge
> reflète un test qui échoue réellement si le flow casse, pas juste une affirmation.
>
> `Okta` `OIDC` `SAML 2.0` `JWT/JWKS` `Bruno CLI` `GitHub Actions`

### 🗝️ [AD-LDAP-Bind-Debug-Lab](https://github.com/Anne-LaureS/AD-LDAP-Bind-Debug-Lab)
> Counterpart "legacy" d'Okta-SSO-Debug-Lab : debug de l'authentification par bind LDAP direct
> contre Active Directory, toujours répandue en entreprise à côté du SSO fédéré. Traduit les
> codes d'erreur AD étendus (`data 52e`, `533`, `701`, `775`...) en diagnostic humain, avec un
> runbook de 8 scénarios de panne (compte désactivé/expiré/verrouillé, bind anonyme, LDAPS non
> configuré...) reproductibles à la demande et testés pour de vrai contre un AD réel.
>
> `PowerShell` `Active Directory` `LDAP` `Legacy Auth`

### 🔁 [IAM-Access-Recertification](https://github.com/Anne-LaureS/IAM-Access-Recertification)
> Boîte à outils de gouvernance des accès IAM inspirée des campagnes de recertification type
> SailPoint : détection de violations de séparation des tâches (SoD), repérage des rôles
> "alibi" quasi-inutilisés, génération et traitement de campagnes de recertification. Ferme la
> boucle sur les données produites par `LDAP-App-Role-Audit`.
>
> `PowerShell` `IAM Governance` `SoD` `Access Recertification`

### 🔄 [IAM-JML-Lifecycle](https://github.com/Anne-LaureS/IAM-JML-Lifecycle)
> Automatisation Joiner/Mover/Leaver sur Active Directory : création de compte avec accès de
> base par département, mise à jour lors d'un changement de poste, désactivation complète à la
> sortie — y compris la gestion du matériel perdu/retrouvé/non rendu. Ferme le cycle de vie que
> `LDAP-App-Role-Audit` et `IAM-Access-Recertification` laissent ouvert : ces deux repos
> détectent et décident quoi faire, celui-ci exécute réellement dans l'annuaire. V2 : chaque
> événement se synchronise aussi vers Okta, testé contre un tenant réel.
>
> `PowerShell` `Active Directory` `Okta` `IAM Lifecycle` `Provisioning`

### ⏱️ [IAM-JIT-PAM](https://github.com/Anne-LaureS/IAM-JIT-PAM)
> Premier volet PAM (Privileged Access Management) : accès juste-à-temps sur Active Directory —
> appartenance à un groupe à privilège accordée pour une durée limitée et une justification
> obligatoires, avec révocation automatique à l'expiration via un registre d'accords, faute de
> mécanisme natif AD accessible sans forêt bastion séparée.
>
> `PowerShell` `Active Directory` `PAM` `Just-In-Time Access`

### 🔍 [LDAP-App-Role-Audit](https://github.com/Anne-LaureS/LDAP-App-Role-Audit)
> Script PowerShell d'audit d'accès applicatifs via LDAP : authentification + sélection des
> applications par popups, recherche récursive application → rôles → membres, export CSV
> (nom, description, nombre et identité des membres par rôle). Testé de bout en bout contre
> un serveur LDAP réel avant publication.
>
> `PowerShell` `LDAP` `IAM` `Access Audit` `LDAPS`

### 🎯 [SOC-Lab-Vulnerability-Assessment](https://github.com/Anne-LaureS/SOC-Lab-Vulnerability-Assessment)
> Rapport de test d'intrusion complet (méthodologie PTES + OWASP) contre un lab Metasploitable3 :
> 11 vulnérabilités critiques (EternalBlue, BlueKeep, GhostCat, injection SQL, XSS...), chaîne
> d'exploitation de bout en bout jusqu'à l'accès SYSTEM/root, remédiations vérifiées.
>
> `PTES` `Metasploit` `Kali Linux` `CVE` `Pentest`

---

## 🏆 TryHackMe Achievements

<div align="center">

| Rank | Rooms Completed | Badges Earned | Streak |
| :---: | :---: | :---: | :---: |
| 🥇 **Top 1%** (#21585) | **221** | **41** | 26 |

</div>

---

## 💻 Tech Stack & Arsenal

#### ⚡ Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

#### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

#### 🔐 IAM & Security
![Active Directory](https://img.shields.io/badge/Active%20Directory-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Okta](https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white)
![LDAP](https://img.shields.io/badge/LDAP-IAM%20Audit-0d1117?style=for-the-badge)
![OIDC](https://img.shields.io/badge/OIDC-Federation-0d1117?style=for-the-badge)
![LDAPS](https://img.shields.io/badge/LDAPS-Encrypted%20Bind-0d1117?style=for-the-badge)

#### 🎯 Offensive Security
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0d1117?style=for-the-badge)
![PTES](https://img.shields.io/badge/PTES-0d1117?style=for-the-badge)

---

## 📡 Connect & Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/annelaures/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Anne-LaureS)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-222222?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Ann3LAu43)

</div>
