# README – Projet de Refonte de l’Application Web M-Motors

## 1. Présentation de l’entreprise

M-Motors est une entreprise spécialisée dans la vente de véhicules d’occasion, créée en 1987. Grâce à la qualité de ses services et à sa politique orientée satisfaction client, l’entreprise est devenue après 30 ans l’une des 10 meilleures entreprises nationales du secteur.

L’entreprise propose :

* Vente de véhicules d’occasion
* Service après-vente
* Financement
* Reprise d’ancien véhicule
* Conseil personnalisé
* Essais routiers

L’entreprise compte environ :

* **800 employés**
* **1 million de clients** au niveau national

---

# 2. Organigramme de l’entreprise

![Image](https://images.openai.com/static-rsc-4/a2FgMHizqqz4imF8O1BqUU2MnMveffYjdeaRIsfwanBK2OvXcYpaOqRdXNcqjF39c4HqpipLgYTJpZp2M1oYbzAVjzNtsOXXs3KuZAE4-JRqKN4ugLzF3U2ycM3DD9SD6VUrgcw08gH0PWzynVMiQoB615eYhsS0siYagGrZfHIG3Uy1wvFjR3Cu-CCgKG2i?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/bTd18HRNPf3Yx5OrjDJYQmYQsHoe904B40f2zqvXuAoTHUXwj5iAF6nu5jaeuqoef6InDOyx5txBsFM-X5Wm4YZzQbV8JbQc3T4ISBiEUe6_ffLr-38EU0WNFDReTnAFfOlEaw--rs1zNCNvWjeu3-ZNUmP0ru0zCQBntMxQbROIGr6iSxTvmizssJkxG98O?purpose=fullsize)

Structure organisationnelle :

* Direction Générale

  * Service Commercial
  * Service Après-Vente
  * Service Financier
  * Service IT
  * Service RH

---

# 3. Contexte du projet

Suite à une étude de marché réalisée par le service commercial, M-Motors souhaite lancer un nouveau service :

## Location Longue Durée avec Option d’Achat (LLD)

Ce nouveau service permettra aux clients de louer un véhicule avec possibilité d’achat final.

### Services inclus ou optionnels

* Assurance tous risques
* Assistance dépannage
* Entretien et SAV
* Contrôle technique

Le projet a été validé par la direction avec un budget important alloué à la refonte complète de l’application web existante.

Un **Product Owner** issu du service commercial a été nommé afin de piloter les besoins métiers.

---

# 4. Objectifs du projet

## Objectif principal

Moderniser l’application web actuelle afin d’intégrer :

* La vente de véhicules
* La location longue durée
* La gestion digitale complète des dossiers clients

---

# 5. Fonctionnalités Front-Office

L’application destinée aux clients devra permettre :

## Gestion des véhicules

* Recherche de véhicules
* Filtre Achat / Location
* Consultation des détails des véhicules

## Gestion des comptes clients

* Création de compte
* Authentification sécurisée
* Gestion de profil client

## Gestion des dossiers

* Dépôt de dossier d’achat ou de location
* Téléchargement des documents justificatifs
* Dossier 100% dématérialisé

## Suivi des demandes

* Consultation de l’état d’avancement du dossier
* Notifications des validations/refus

---

# 6. Fonctionnalités Back-Office

L’application d’administration devra permettre :

## Gestion des véhicules

* Ajouter un véhicule à vendre
* Ajouter un véhicule à louer
* Modifier les informations d’un véhicule
* Supprimer un véhicule

## Gestion des statuts

* Basculer un véhicule :

  * Vente → Location
  * Location → Vente

## Gestion des dossiers clients

* Visualisation des dossiers
* Validation des dossiers
* Refus des dossiers
* Historique des traitements

---

# 7. Contraintes techniques

Le service IT a défini plusieurs contraintes importantes :

## Haute disponibilité

Définition des indicateurs :

### Recovery Point Objective (RPO)

Temps maximal acceptable de perte de données.

### Recovery Time Objective (RTO)

Temps maximal acceptable pour remettre le service en fonctionnement après incident.

---

# 8. Architecture technique

L’architecture devra être modernisée afin de :

* Supporter un grand nombre d’utilisateurs
* Garantir la disponibilité des services
* Assurer la sécurité des données
* Faciliter l’évolution future de l’application

## Éléments techniques prévus

* Nouvelle base de données
* Migration des données existantes
* API sécurisée
* Hébergement Cloud
* Sauvegardes automatiques
* Monitoring système

---

# 9. Move To Cloud

Le projet inclut une opération stratégique :

## Migration vers le Cloud

Objectifs :

* Scalabilité
* Réduction des coûts d’infrastructure
* Haute disponibilité
* Sauvegarde et reprise après incident
* Sécurité renforcée

Exemples de solutions possibles :

* AWS
* Microsoft Azure
* Google Cloud Platform

---

# 10. Acteurs du projet

| Acteur             | Rôle                            |
| ------------------ | ------------------------------- |
| Direction Générale | Validation stratégique          |
| Product Owner      | Définition des besoins métiers  |
| Service Commercial | Étude de marché et suivi métier |
| Service IT         | Développement et architecture   |
| Clients            | Utilisateurs de la plateforme   |

---

# 11. Méthodologie proposée

Méthode Agile Scrum :

* Sprint planning
* Daily meeting
* Sprint review
* Sprint retrospective

## Rôles Scrum

* Product Owner
* Scrum Master
* Équipe de développement

---

# 12. Sécurité

Mesures de sécurité recommandées :

* Authentification sécurisée
* Chiffrement des données
* Sauvegardes régulières
* Gestion des accès
* Protection contre les cyberattaques

---

# 13. Conclusion

Le projet de refonte de l’application web M-Motors représente une étape stratégique importante pour l’entreprise. L’intégration du service de location longue durée permettra de diversifier les offres commerciales et d’améliorer l’expérience client.

La modernisation de l’architecture, la migration vers le cloud et la digitalisation complète des dossiers permettront également d’assurer une meilleure performance, sécurité et évolutivité du système d’information.

