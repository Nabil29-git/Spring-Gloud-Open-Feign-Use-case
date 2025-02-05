﻿# SPRING CLOUD 
1. Créer le micro service Customer-service • Créer l’entité Customer • Créer l’interface CustomerRepository basée sur Spring Data • Déployer l’API Restful du micro-service en utilisant Spring Data Rest • Tester le Micro service
2. Créer le micro service Inventory-service • Créer l’entité Product • Créer l’interface ProductRepository basée sur Spring Data • Déployer l’API Restful du micro-service en utilisant Spring Data Rest • Tester le Micro service
3. Créer la Gateway service en utilisant Spring Cloud Gateway
1. Tester la Service proxy en utilisant une configuration Statique basée
sur le fichier application.yml
2. Tester la Service proxy en utilisant une configuration Statique basée
une configuration Java
4. Créer l’annuaire Registry Service basé sur NetFlix Eureka Server
5. Tester le proxy en utilisant une configuration dynamique de Gestion des
routes vers les micro services enregistrés dans l’annuaire Eureka Server
6. Créer Le service Billing-Service en utilisant Open Feign pour
communiquer avec les services Customer-service et Inventory-service
7. Créer un client Angular qui permet d’afficher une facture


## Première Partie 

### Actuator : 
![actuator](https://user-images.githubusercontent.com/86847138/200059853-129d8fe5-891a-4bd1-9646-207b3034a034.PNG)


### Actuator Beans : 
![actuator beans](https://user-images.githubusercontent.com/86847138/200059870-33c4bbf7-8912-48c5-aa20-63d0dbd44e1a.PNG)


### Actuator Env :
![actuator env](https://user-images.githubusercontent.com/86847138/200059925-311548f7-4965-4381-975e-04323f7c6b2b.PNG)


### Customer H2 Console :
![h2 console](https://user-images.githubusercontent.com/86847138/200059608-07b33ed6-96cd-444d-83ff-79a1e6b5cabb.PNG)


### Product H2 Console :

![h2 console inventory](https://user-images.githubusercontent.com/86847138/200059654-8b5662ca-fee2-4b70-b1ef-666083d05435.PNG)


### Customers with gateway : 
![customers 8888](https://user-images.githubusercontent.com/86847138/200060024-cdac0216-3801-4944-bf5f-3157a8980def.PNG)


### Products with gateway : 
![products 8888](https://user-images.githubusercontent.com/86847138/200060063-dc514efb-1641-44bc-9e37-1f7d0ffa6180.PNG)


### Id :

![products 8888 id](https://user-images.githubusercontent.com/86847138/200060118-2a85d4f4-27c2-45bf-8276-861e5d1f1f8b.PNG)



### Eureka before enabling Discovery Service :
![eureka before](https://user-images.githubusercontent.com/86847138/200060276-bff3e8ad-383f-46c7-b8de-fa1f53b46f7e.PNG)



### Eureka after enabling Discovery Service :
![eureka after](https://user-images.githubusercontent.com/86847138/200060309-644371cc-e1a7-40cb-a9ea-4e83ba7bff12.PNG)


### Customers with id using the Web Service :

![CUSTOMER SERVICE](https://user-images.githubusercontent.com/86847138/200060405-2f2684d3-92c3-41fb-88a8-4d3910bc5c69.PNG)



## Deuxième Partie : 

### H2 Console Bill :
![h2 console bill](https://user-images.githubusercontent.com/86847138/200087300-68a674d4-4308-4775-8363-2fb78ac3cded.PNG)




### H2 Console Product Item : 
![h2 console product item](https://user-images.githubusercontent.com/86847138/200087326-069e0b07-5d23-473f-9fb3-4c4810432c91.PNG)



### Billing Service toutes les données :
![billing-service all data](https://user-images.githubusercontent.com/86847138/200087372-36bbc5a6-3876-47dd-827a-5068c19c7640.PNG)



### Billing Service selon la donnée dont on a besoin (name dans le screenshot) : 
![billing-service selo le besoin (name)](https://user-images.githubusercontent.com/86847138/200087460-274e02b2-2c3a-4e82-8319-53d9494e7404.PNG)









