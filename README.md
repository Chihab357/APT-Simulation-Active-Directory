# APT-Simulation-Active-Directory
Simulation d'une attaque APT sur un environnement Active Directory avec mesures de défense (prévention, détection, réponse).

# 🛡️ Simulation d'une attaque APT sur une infrastructure Active Directory

Bienvenue dans ce dépôt GitHub dédié à la **simulation d'une attaque APT (Advanced Persistent Threat)** sur une infrastructure virtuelle d’entreprise basée sur **Active Directory**.  
Ce projet a été réalisé dans le cadre de mon stage de fin d'études chez **AXA GBS**.

---

## 🧠 Résumé du projet

Ce lab reproduit un scénario réaliste d'attaque avancée visant une entreprise fictive nommée **STRIXCORP**, suivie de la mise en place de **contre-mesures défensives**.

<p align="center">
<img width="534" height="603" alt="image" src="https://github.com/user-attachments/assets/969d8b84-2b56-46d8-b842-ae5c016075fa" />
</p>

---

## 📋 Contexte & Objectifs

- 🔍 **Reproduire un scénario APT** incluant toutes les étapes : reconnaissance, accès initial, escalade de privilèges, mouvement latéral, persistance.
- 🛠️ **Mettre en place une infrastructure d’entreprise** réaliste sous VMware.
- 🧪 **Tester des outils offensifs** comme Metasploit, Responder, CrackMapExec, etc.
- 🔐 **Déployer des mécanismes de défense** : Wazuh, Suricata, Sysmon, GPO, segmentation réseau.
- 📊 **Comparer l’état de l’infrastructure avant et après sécurisation**.

---

## 🧰 Prérequis

- VMware Workstation Pro  
- 1 x Windows Server 2022  
- 2 x Windows 10 Pro  
- 1 x Kali Linux  
- (Optionnel) 1 x Ubuntu Server pour SIEM

---

## ⚔️ Étapes de l'attaque simulée (MITRE ATT&CK)

| Phase                   | Tactic             | Technique ID |
|-------------------------|--------------------|--------------|
| 🔍 Reconnaissance        | External            | T1593        |
| 📥 Accès initial         | Spear Phishing      | T1566.001    |
| 💥 Exploitation          | Malicious Payload   | T1059.003    |
| 🔓 Escalade de privilèges | Admin Tools Abuse   | T1548.002    |
| 🔁 Mouvement latéral     | SMB Relay           | T1021.002    |
| 🪝 Persistance           | Backdoor implant    | T1053.005    |

---

## 🛠️ Outils utilisés

### Offensive

- Metasploit Framework / msfvenom  
- Responder / SMBClient / Evil-WinRM  
- CrackMapExec / Impacket  
- Hashcat / Nmap / Enum4linux  
- MongoDB / NoSQL Injection  
- Payloads Word piégés  

### Défensive

- Wazuh + Kibana  
- Sysmon + Winlogbeat  
- Suricata  
- Windows Defender  
- GPO / Hardening  
- Event Viewer  

<p align="center">
<img width="416" height="119" alt="image" src="https://github.com/user-attachments/assets/dac23105-4dfe-4c22-b028-7fbc9750b385" />
</p>

---

## ⚠️ Avertissements

- ⚠️ À usage éducatif uniquement.  
- ⚠️ Ne jamais utiliser ce code ou ces techniques sur des environnements réels ou en production.  
- ⚠️ Exécution à faire uniquement dans un lab virtuel isolé.

---

## 👨‍💻 Auteur

**Chihab Medaghri Alaoui**  
Cycle Ingénieur 5A – Cybersécurité  
Stage chez **AXA GBS**

<p align="center">
<img width="954" height="203" alt="image" src="https://github.com/user-attachments/assets/48164b74-7ecc-4319-afdf-78584455632f" />
</p>

---

## 📜 Licence

Projet académique réalisé dans le cadre d’un stage de fin d’études.  
Usage libre pour l’apprentissage personnel ou universitaire.  
**Interdit à des fins malveillantes.**
