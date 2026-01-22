Future Interns - Cyber Security Internship

Tâche 1: Audit de Sécurité web - Analyse Passive

Informations Stagiaire
-	Nom : ANANIVi komlanvi
- 	Affectation : Tâche 1 - Analyse passive des vulnérabilités web
- 	Cible : Gin and Juice Shop
- 	Date : 21 janvier 2026

Outils utilisés & Environnement

-	Scanning Tool: OWASP ZAP (Analyse passive) 
-	Documentation : Canva (Outil de reporting)
-	Système d’exploitation : Windows 
-	Platform : GitHub        


Aperçu du projet

Cette tâche avait pour objectif de réaliser une évaluation de vulnérabilité non-intusive sur une application web réelle en lecture seule afin d’identifer les failles de configuration, d’évaluer leur impact potentiel et de proposer des mesures correctives concrètes.
Ce projet simule une phase de reconnaissance et d’audit de surface telle qu’elle est pratiquée lors d’un test d’intrusion professionnel (Pentest).

Méthodologie

Environnement Setup : Choix d’un domaine public autorisé pour les tests (ginandjuice.shop).

Reconnaissance : utilisation du «ZAP Spider» pour cartographier l’arborescence du site sans interaction malveillante.

Analyse Passive : Analyse des flux HTTP, des en-têtes de sécurité et des scripts chargés par le navigateur (lecture seule).

Analyse : Identification des composants obsolètes et classifications des risques selon la gravité

Reportage : Création d'un rapport visuel sur Canva incluant les preuves (screenshots) et les recommandations.


Principale constatation

L’analyse a révélé 15 alertes de sécurité, classées selon le framework OWASP:

Sévérité Elevée : Vulnerable JS library - Angular JS 1.7.7 (A06:2021 - Vulnerable and Outdated Components) 

Sévérité Moyenne: Absence de Jetons Anti-CSRF (A01:2021 - Broken Access Control)

Sévérité Faible : Cookie Security (Missing Secure/HttpOnly flags)

Livrables

-	Rapport PDF: Rapport d’audit complet conçu avec Canva
-	Preuves : Dossier contenant les captures d’écran des alertes critiques identifiées dans OWASP ZAP

Ce projet a été réalisé dans un cadre strictement éthique sur un site de test autorisé, conformément au programme de stage Future Interns.*



