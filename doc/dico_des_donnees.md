# Dictionnaire de données

## Tasks (`tasks`)

|Champ|Type|Spécificités|Description|
|-|-|-|-|
|id|INT|PRIMARY KEY, NOT NULL, UNSIGNED, AUTO_INCREMENT|L'identifiant de la tâche|
|name|VARCHAR(64)|NOT NULL|Le nom de la tâche|
|categorie_id|INT|NOT NULL|L'id de la catégorie de la tâche|
|status_id|INT|NOT NULL|L'id du status de la tâche|
|created_at|TIMESTAMP|NOT NULL, DEFAULT CURRENT_TIMESTAMP|La date de création de la tâche|
|updtated_at|TIMESTAMP|NOT NULL, DEFAULT CURRENT_TIMESTAMP|La date de dernière modification de la tâche|

## Category (`category`)

|Champ|Type|Spécificités|Description|
|-|-|-|-|
|id|INT|PRIMARY KEY, NOT NULL, UNSIGNED, AUTO_INCREMENT|L'identifiant de la catégorie|
|name|VARCHAR(64)|NOT NULL|Le nom de la catégorie|
|created_at|TIMESTAMP|NOT NULL, DEFAULT CURRENT_TIMESTAMP|La date de création de la catégorie|
|updtated_at|TIMESTAMP|NOT NULL, DEFAULT CURRENT_TIMESTAMP|La date de dernière modification de la catégorie|

## Status (`status`)

|Champ|Type|Spécificités|Description|
|-|-|-|-|
|id|INT|PRIMARY KEY, NOT NULL, UNSIGNED, AUTO_INCREMENT|L'identifiant du status|
|name|VARCHAR(64)|NOT NULL|Le nom du status|
|created_at|TIMESTAMP|NOT NULL, DEFAULT CURRENT_TIMESTAMP|La date de création du status|
|updtated_at|TIMESTAMP|NOT NULL, DEFAULT CURRENT_TIMESTAMP|La date de dernière modification du status|
