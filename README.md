<img style="float: right;" src="images/component_engineering.svg" alt="EngineeringAISystems" width="250"/>

# MGL7320 - Ingénierie logicielle des systèmes d'IA

## Cours  basé sur [SE4AI Training Program](https://github.com/create-se4ai/engineering-ai-systems-course) :

<img style="float:right;" align="right" src="images/logo.svg" alt="SE4AI" width="150"/>

>This course is part of the [SE4AI Training Program](https://www.se4ai.org/), a training program on the development, deployment and servicing of Artificial Intelligence-based Software Systems. The program was established in collaboration world-renowned researchers and technology leaders and is composed of four Canadian universities: Concordia University, Polytechnique Montréal, Queens University, and the University of Alberta.  
>
>This particular version of the course was given as a special course at [UQAM](www.uqam.ca) in the Winter of 2023, under the slot course MGL7811 - Sujets spéciaux en génie logiciel II.
Hence, the description below - in French - is specific to this version of the course.
Alongside the language differences, there are other specific changes to the original material:
1. The course was structured to be given in 15 weeks, instead of 13 weeks. Hence, a few new modules were added.
2. The course was structured as a practical course, instead of research oriented. Students have to develop a project, which is presented at the end of the course. The project is developed in groups of 3-4 students and has a practical component (i.e., developing a software system) and a research component (i.e., writing a report and presenting the results). More details about this can be found in the [course-project](./course-project) folder.
1. The original set of papers were also updated as well as the slides style and content.

<img style="float:right;" align="right" src="https://www.clipartmax.com/png/small/30-303903_traffic-cone-clip-art-traffic-cone-clip-art.png" alt="Traffic Cone Clip Art - Traffic Cone Clip Art @clipartmax.com" width="150"/>

## Travail en cours !!!

- ~~Contenu susceptible d'évoluer~~ Ce contenu devrait évoluer
- Disponible (provisoirement) sur [https://github.com/lomagnin/MGL7320-automne-2023](https://github.com/lomagnin/MGL7320-automne-2023)

# Description du cours

Ce cours vise à fournir les concepts clés liés à l'ingénierie des systèmes d’intelligence artificielle. Les sujets inclus sont la spécification et l’architecture des systèmes d’intelligence artificielle, la validation et la gestion des données, le processus de sélection des modèles, les tests ainsi que le déploiement des systèmes d'intelligence artificielle. Les sujets spéciaux sur l'interprétation, l’équité et les opérations des systèmes d’intelligence artificielle peuvent aussi être inclus.

## Objectifs d'Apprentissage du Cours

L’objectif du cours est de fournir aux étudiants gradués les connaissances techniques de base et fondamentales tout en appliquant les concepts et processus de génie logiciel (GL) dans le contexte d’un système d’intelligence artificielle (IA). À la fin de ce cours, les étudiants seront capables d’identifier les enjeux liés aux systèmes d’intelligence artificielle et de proposer un ensemble de solutions pour spécifier, développer et maintenir les systèmes d’intelligence artificielle. Le cours se concentre sur l’interconnexion du GL et de l’IA, et sur la manière dont les sujets couverts s’appliquent aux systèmes basés sur l’IA.

<h2><p style="text-align: center;">
<img style="float:center;" align="center" src="https://ml-ops.org/img/mlops-loop-en.jpg" width="450"/><br>
<a href="https://ml-ops.org/content/mlops-principles">MLOPs</a>  
</p></h2>

# Présentation du chargé de cours (Dr. Laurent Magnin)
- Doctorat en Intelligence Artificielle (1996)
  - Anciennement chercheur en IA
  - Chargé de cours / professeur associé
- Consultant:
  - Systèmes experts
  - Big Data
- Développeur / Architecte
- Travaille présentement pour une compagnie d'assurance
  - Architecte IA
  - Scientifique de données

# Contenu du cours

## Format des séances
- Les jeudis 18h00 à 21h00 (présentiel)  
- Salle [SH-3540 | Campus de Montréal](http://carte.uqam.ca/#pavillon/sh)  
- 10 minutes de pause (Disponible pour répondre aux questions)

Les séances:
- Inclurent des discussions actives
- Exercices pratiques
- Utilisation de [Kahoot](https://kahoot.it)

## Classe d’Ingénierie
<img style="float:right;" align="right" src="images/keep_calm.png" alt="keep_calm"  width="150"/>

Concentré sur le jugement d’ingénierie
- « Trade-offs » et justifications plutôt qu’une seule bonne réponse
- Engagement pratique

Non axé sur:
- les garanties formelles ou
- les principes fondamentaux d’IA

<p style="text-align: center;"><b>Balance entre théorie :bulb: (pdf) & aspects pratiques :nut_and_bolt: </b></p>

Tentative : travail sur des environnements <i>Cloud</i>.

## Ce qui est attendu de vous

- Assister à des conférences et participer à des discussions

- Faites les lectures et les devoirs assignés!

- Travaillez sur votre projet en continu.

- Apportez vos idées et vos préoccupations en classe

- **Posez des questions.**

## Calendrier

Le calendrier ci-dessous **est susceptible d’évoluer**.

| Semaine | Sujet | Date |
| ------- | ----- | ---- |
| 1		    | [Introduction et aperçu de l’intelligence artificielle (IA)](./lectures/01_introduction/01_introduction_slides.pdf) | 7 septembre |
| 2	      |	[IA pour les ingénieurs logiciels (Activité pratique)](./lectures/02_mlpipelines_practical/02_ml_pipelines_practical_slides.pdf)      | 14 septembre |
| 3		    | [Exigences et spécifications des systèmes d'IA](./lectures/03_requirements/03_requirements_slides.pdf)               | 21 septembre |
| 4       | [Architecture des systèmes d'intelligence artificielle](./lectures/04_architecture/04_architecture_slides.pdf)       | 28 septembre |
| 5	      |	[Validation et gestion des données](./lectures/05_data_validation/05_data_validation_slides.pdf) | 5 octobre |
| 6	      | [Sélection des modèles](./lectures/06_model_selection/06_model_selection_slides.pdf)         | 12 octobre |
| 7     	| Mises à jour des projets (présentations faites par les étudiants) | 19 octobre |
| 8       | Semaine de lecture ou de relâche | 26 octobre |
| 9       | [Test des systèmes d'intelligence artificielle](./lectures/09_testing/09_testing_slides.pdf)  | 2 novembre |
| 10      | [Déploiement des systèmes d'intelligence artificielle](./lectures/10_deploying/10_deploying_slides.pdf) | 9 novembre |
| 11      |	[Confiance dans la prédiction et l'explicabilité du modèle](./lectures/11_explanation_trust/11_explanation_slides.pdf) | 16 novembre |
| 12		  | [Sujets spéciaux: l'applicabilité de modèles des langages](./lectures/12_special_topic/12_special_topic_slides.pdf) | 23 novembre |
| 13		  | Présentations des projets (présentations faites par les étudiants) | 30 novembre |
| 14      |	Examen | 7 décembre |
| 15		  | Conclusion du cours | 14 décembre |

# Évaluation

**À déterminer**

# Médiagraphie

Le cours [originel] fera occasionnellement référence au manuel suivant :
- Building Intelligent Systems: A Guide to Machine Learning Engineering, 2018. Geoff Hulten

Autres références :
- [The Big Book of MLOps](https://www.databricks.com/resources/ebook/the-big-book-of-mlops) (copie gratuite)

## Questions et communication

- Par courriel : magnin [dot] laurent_yves [at] uqam [dot] ca (Inclure [MLG7320] dans le titre du message)

- Planifiez une réunion en personne/Zoom si nécessaire. Je resterai 15 minutes après le cours (la plupart des cours).

- Poser la question dans la séance

- Discutez avec vos camarades de classe

## Want to use any of the course's materials?

> You are free to use and distribute the course's material as long as you:
- **Abide by the license**, please check the [LICENSE](LICENSING.md) conditions
- **Notify us** and let us know how you plan to use the material using the contact e-mails below. There is no vetting process in place, we just want to be notified to have control of who is using the material.
>
> You can cite this repository using the following BibText entry, if you plan to use this material in a scientific work:
```
@misc{SE4AI_course,
author = {Emad Shihab and Diego Elias Costa},
title = {SE4AI course: Engineering AI-Based Software Systems},
publisher = {Data-Driven Analysis of Software (DAS) Lab, Concordia University},
note = {https://github.com/create-se4ai/engineering-ai-systems-course}
}
```