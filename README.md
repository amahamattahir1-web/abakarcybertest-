<h1>Bonjour, je suis Abakar Mahamat Tahir Hassan 👋</h1>

### 🎓 Étudiant en BTS SIO option SISR (2ème année)
Passionné par les **réseaux, les systèmes et la cybersécurité**, je me forme à l'administration d'infrastructures informatiques. Je recherche [un stage / une alternance / un poste] en [administration systèmes et réseaux / support / cybersécurité] à partir de [date].

---

## 🛠️ Compétences

- **Systèmes :** Windows Server 2022, Linux Debian
- **Services réseau :** Active Directory (AD DS), GPO, DNS, DHCP, partages de fichiers
- **Sauvegarde et réplication :** RSync
- **Réseaux :** adressage IP, plages DHCP, zones DNS directes/inverses, passerelle/pare-feu
- **Outils :** [VMware / VirtualBox / Packet Tracer / GLPI / Wireshark...]

---

## 📁 Mes projets BTS SIO SISR

### 🏟️ Mission 2 : Infrastructure StadiumCompany (domaine `stadiumcompany.local`)

**Contexte :** déploiement et administration de l'infrastructure d'une entreprise. Les serveurs principaux sont hébergés au stade, dans le centre d'hébergement informatique, et certains services sont répliqués sur les sites.

**Ce que j'ai réalisé / étudié :**

- **Active Directory :** création du domaine `stadiumcompany.local` et organisation en UO par service (Administrateur, Equipe, Restaurant, Fournisseur, VIP-Presse, WIFI, Camera-IP).
  - Chaque UO contient les utilisateurs, un groupe `G_xxxx`, un groupe à privilèges `GP_Admin` et une GPO dédiée.
  - Logins au format `pnom` (première lettre du prénom + nom), avec un chiffre de 1 à 10 en cas d'homonymie.
- **GPO (exemple `gpo_equipes`) :**
  - blocage du panneau de configuration et des paramètres réseau
  - script de démarrage `Equipesstart.bat` pour connecter les lecteurs réseau
  - bureau imposé (barre de menu, fond d'écran)
- **Utilisateurs :** dossier personnel et profil centralisé pour chacun, avec une stratégie de complexité des mots de passe au niveau du domaine.
- **DNS :** zone directe `stadiumcompany.local` et zone inverse, avec un serveur primaire (Windows Server 2022) et un secondaire (Linux Debian).
- **DHCP :** plage `172.20.0.x/24`, avec passerelle/pare-feu et serveurs DNS transmis via les options DHCP.
- **Stockage et réplication :** stockage des fichiers utilisateurs et serveur RSync.

**Technologies :** Windows Server 2022 · Active Directory · GPO · DNS · DHCP · Debian · RSync

📄 [Documentation du projet](lien) · 🖼️ [Schéma réseau](lien) · 🎥 [Démonstration](lien)

### 📌 Mission 1 : [Titre du projet]
[Description courte : contexte, ce que tu as fait, technologies]
📄 [Documentation](lien)

---

## 🔎 Veille technologique
[Sujet de ta veille : ex. cybersécurité, Windows Server, zero trust...] → [lien vers ta veille]

## 📜 Formation et certifications
- BTS SIO option SISR (en cours) : [nom de l'établissement]
- [Baccalauréat, certifications : Cisco CCNA, Microsoft, etc.]

---

## 🤳 Me contacter
📧 [ton.email@exemple.com]
💼 [LinkedIn](lien)
💻 [GitHub](lien)
