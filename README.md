
# Projet de Gestion des Étudiants avec Spring Boot

# Aperçu

Ce projet est une application de gestion des étudiants développée avec Spring Boot. Il permet la création et la gestion d'étudiants, de filières et de rôles d'utilisateur, tout en offrant des fonctionnalités avancées telles que l'affichage des éléments cités et la possibilité de lister les étudiants par filières. L'application est également documentée via Swagger pour une utilisation aisée des API exposées.

![schema-generale-spring](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/2ec1f6c8-f079-4e4d-a5b5-fe5744c48b54)

# Technologies Utilisées

- **Spring Boot:** Framework Java pour le développement d'applications d'entreprise.
- **Java:** Langage de programmation principal.
- **MySQL:** Système de gestion de base de données relationnelle pour le stockage des données.
- **Swagger:** Outil de documentation d'API pour faciliter l'exploration des API exposées par l'application.

# Fonctionnalités Clés

1. **Gestion des Étudiants:** Création, mise à jour et suppression d'étudiants avec des informations telles que le nom, le prénom, etc.

2. **Gestion des Filières:** Ajout, modification et suppression de filières académiques.

3. **Gestion des Rôles:** Création, attribution et révocation de rôles aux utilisateurs, avec des relations many-to-many bidirectionnelles.

4. **Affichage des Éléments Cités:** Visualisation détaillée des informations des étudiants, des filières et des rôles pour une meilleure compréhension.

5. **Affichage des Étudiants par Filières:** Liste des étudiants organisés par filière, pour un accès rapide aux informations par groupe.

6. **API Swagger:** Documentation et exploration des API via Swagger, facilitant l'intégration avec d'autres services.

# Captures d'écran 
# Test au niveau de Postman

## Test de l'ajout et l'affichage

![post-postman-student1](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/a5be265c-eb6d-4fa4-80bd-b5d2d1225f02)
![post-postman-student2](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/938e215a-ab42-4720-af96-694b023dd41b)

## Test de la suppression

![post2](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/8ca254a4-b8e4-4e34-af5c-f930fe94b2a6)

![get-post2](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/759cb814-6b1b-4b8c-a932-db49e83d9ba5)

![delet-post2](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/9d9c8950-6f0e-43a9-beb8-cbc629205f12)
![result-delete-post2](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/d2e6984b-0403-4bbe-b883-bf2f2ee69957)

## Test de filtrage des étudiants par filière
![afficher-stud-fili](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/a3159fa3-f273-4188-9172-b074955174a0)

# Test  au niveau de Swagger
![swgg-ajou-fil1](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/1affd0ae-44c1-43e1-abf5-b1668fd9374c)
![swgg-ajout-fil2](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/b4a5cbb7-33ca-4c24-9183-1e0dab827dbc)
![swgg-ajou-role1](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/70bd3e98-59c4-436e-af8b-4d01008795e3)
![swgg-ajou-role-2](https://github.com/BasmaGd/tp-SpringBootSwagger/assets/118211411/fcd6a983-5d6c-4de5-bb15-46df1972c57e)
