# Prevent'IS — Écosystème pédagogique Preventys

> Formation CQPM QSE · Organisme Preventys · Qualiopi

🌐 **Site en ligne** : [https://preventis.github.io/preventis/](https://preventis.github.io/preventis/)

---

## Accès direct

| Outil | Lien | Rôle |
|-------|------|------|
| 🗓 Prevent'Road | [prevent_road.html](prevent_road.html) | Portail principal — planning journalier |
| 🃏 Prevent'Cards | [preventcards_parcours__2_.html](preventcards_parcours__2_.html) | 84 cartes pédagogiques · PERT · Profils |
| 📊 QRAFT Obeya | [preventis_obeya_qraft_v2__2_.html](preventis_obeya_qraft_v2__2_.html) | Pilotage promotion 75 jours |
| 🚨 Prevent'Andon | [prevent_andon.html](prevent_andon.html) | Alertes dysfonctionnement temps réel |
| 📈 Dashboard | [preventis_dashboard.html](preventis_dashboard.html) | Tableau de bord formation |
| 🤖 Prevent'Assist | [prevent_assist.html](prevent_assist.html) | Assistant IA pédagogique Socratique |
| 📝 Prevent'Exam | [prevent_exam.html](prevent_exam.html) | Assistant mémoire CQPM |
| 🔍 Prevent'Veille | [prevent_veille.html](prevent_veille.html) | Veille réglementaire Qualiopi (Ind. 32) |
| 📚 Prevent'Agil | [Digipad →](https://digiwall.app/w/3339/e0a26/preventagil) | Cours en ligne formateurs |
| 📐 Form'Agil | [FormAgil_Didacticiel1_Mere.html](FormAgil_Didacticiel1_Mere.html) | Didacticiel pédagogique |

---

## Structure de l'écosystème

```
preventis/
├── index.html                          ← Page d'accueil (redirection auto)
├── prevent_road.html                   ← Portail principal
├── preventcards_parcours__2_.html      ← 84 cartes pédagogiques
├── preventis_obeya_qraft_v2__2_.html   ← QRAFT Obeya
├── prevent_andon.html                  ← Andon
├── preventis_dashboard.html            ← Dashboard
├── prevent_assist.html                 ← IA pédagogique
├── prevent_exam.html                   ← Assistant mémoire CQPM
├── prevent_veille.html                 ← Veille réglementaire
├── FormAgil_Didacticiel1_Mere.html     ← Form'Agil
├── preventis_architecture.html         ← Documentation technique
└── README.md                           ← Ce fichier
```

---

## Mettre à jour un fichier

1. Aller sur [github.com/preventis/preventis](https://github.com/preventis/preventis)
2. Cliquer **Add file → Upload files**
3. Glisser-déposer le fichier modifié
4. Cliquer **Commit changes**
5. En ligne dans ~2 minutes ✅

---

## Technologie

Fichiers HTML statiques autonomes — aucune dépendance serveur, aucune base de données.  
Les données (états QRAFT, veille réglementaire) sont sauvegardées dans le **localStorage** du navigateur.  
Le partage d'état se fait par **URL encodée** (paramètre `?s=`).

---

*Preventys · Formation CQPM QSE · Qualiopi*
