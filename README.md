# Automatisation du traitement de fichiers Excel pour un département de Ressources Humaines 📊
<br>

**English version below**
<br>

👨‍🎓 Projet réalisé dans le cadre de la formation diplômante "Data Analyst" d'OpenClassRooms.
<br>🛠 Mots clés : **normes RGPD, automatisation, KNIME, workflow, Excel.**

---

Le projet en quelques mots :

Un département (fictif) des ressources humaines nous demande d'automatiser le traitement de 3 fichiers Excel qu'ils utilisent régulièrement.
Ces fichiers Excel sont générés de manière automatique par leur ERP et nécessitent de nombreux retraitements récurrents, notamment pour "gommer" certaines informations sensibles.

Nous avions donc pour mission de construire un processus d'automatisation qui évite au département RH de perdre de précieuses heures à retraiter ces fichiers chaque mois.

Notre processus devait être capable :
  1) de générer à partir de ces trois fichiers Excel un fichier Excel final unique respectant les normes RGPD et contenant uniquement des informations utiles.
  2) cinq indicateurs graphiques (égalité salariale, différences de temps de travail, répartition des effectifs par catégorie professionelle et par sexe, etc) 

Les utilisateurs devaient en outre pouvoir utiliser le processus de manière récurrente, rapidement et sans connaissance technique particulière.

L'objectif a été atteint en construisant un workflow via le logiciel KNIME.

Dans le repository, on pourra trouver :
- Les trois fichiers Excel d'entrée (*"Table remuneration", "Table salariés", "Table infos pros"*)
- Le fichier Excel de synthèse de sortie (*"Synthèse finale"*), respectant les RGPD.
- Des copies d'écran du Workflow KNIME (le format KNIME ne permet pas de partager le Workflow tel quel sur cette plateforme).
- Des copies d'écran des indicateurs graphiques générés par le workflow KNIME en sortie (*"Indicateur généré 1", 2, 3*, etc).

---

👋 Merci de votre lecture !<br>
✏️ N'hésitez pas à me contacter si vous avez des remarques ou questions via [mon Linkedin](https://www.linkedin.com/in/florian-thouraud)
<br>

<br>

## ENGLISH VERSION : Automating the processing of Excel files for a Human Resources department 📊

👨‍🎓 Project carried out as part of the OpenClassRooms "Data Analyst" diploma course.
<br>🛠 Key words : **GDPR standards, automation, KNIME, workflow, Excel.**

---

The project in a nutshell:

A (fictitious) human resources department asked us to automate the processing of 3 Excel files that they use regularly.
These Excel files are generated automatically by their ERP and require a lot of recurring reprocessing, in particular to 'erase' certain sensitive information.

Our brief was therefore to build an automation process that would save the HR department precious hours of reprocessing these files every month.

Our process had to be able to:
  1) generate a single final Excel file from these three Excel files, complying with RGPD standards and containing only useful information.
  2) five graphical indicators (equal pay, differences in working hours, breakdown of workforce by professional category and gender, etc.). 

Users also needed to be able to use the process repeatedly, quickly and without any particular technical knowledge.

This objective was achieved by building a workflow using KNIME software.

The repository contains :
- The three input Excel files (*"Remuneration table", "Employee table", "Professional info table "*)
- The Excel output summary file (*"Final summary "*), in compliance with the RGPD.
- Screenshots of the KNIME Workflow (the KNIME format does not allow the workflow to be shared on this platform in its current form).
- Screenshots of the graphical indicators generated by the KNIME workflow (*"Indicator generated 1", 2, 3*, etc).

---

👋 Thank you for your time <br>
✏️ Please if you have any question or remark feel free to contact me via [my Linkedin](https://www.linkedin.com/in/florian-thouraud)

