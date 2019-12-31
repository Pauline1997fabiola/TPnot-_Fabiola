Etape 5: Description des dépendances.
Web: permet de communiquer facilement avec des API web.
JPA: permet d'utiliser le sql et les bases de données.
Hibernate: permet une connexion et une relation avec la base de données plus facilement .
H2: système de gestion de base de données relationnelles écrit en java.
Devtools: offre des outils en plus pour le développement.
Thymeleaf: permet de générer du html en java.

Etape 13:
1) @GetMapping("/greeting") est la partie du code qui a permit à paramétrer l'url d'appel /greeting.
2)Pour choisir le fichier html à afficher, nous avons utilisé return "greeting".
3)Pour envoyer le nom de celui à qui nous disons bonjour avec le second lien, on utilise @RequestParam(name="nameGET", required = false, defaultValue="world")

Etape 17:
La table adresse a été créée.

Etape 18:
Hibernate permet d'accéder à la base de donnée à l'aide des annotations, et vue que la table n'existait pas, il l'a créée.

Etape 20:
Lorsqu'on fait une reqête de type SELECT, on voit tout le contenu de la table adresse ajouter dans le fichier Data.sql.

Etape 23:
L'annotatio @Autowired permet de faire l'injection de dépendances entre les beans de l'application.

Etape 30:
Pour ajouter bootstrap à notre projet, nous avons ajouter dans notre fichier pom les dépendances suivantes:
		<dependency>
			<groupId>org.webjars</groupId>
			<artifactId>bootstrap</artifactId>
			<version>3.3.6</version>
		</dependency>

		<dependency>
			<groupId>org.webjars</groupId>
			<artifactId>bootstrap-datepicker</artifactId>
			<version>1.0.1</version>
		</dependency>

		<dependency>
			<groupId>org.webjars</groupId>
			<artifactId>jquery</artifactId>
			<version>1.9.1</version>
		</dependency>
		
Etape 6 partie 2:
1)Oui il faut une clé pour l'api Darksky.
2)L'URL appelé est la suivante: https:api.darksky.net/forecast/clé/lat,lon
3)La méthode http utilisée est un GET.
4)Les paramètres d'appels sont passés de la manière suivante: https://api.darksky.net/forecast/clé/lat,lon?option=val
5)pour afficher la température l'information est dans 55.62 et pour afficher les prévisions de météo l'information est dans le daily. 

Etape 7 partie 2:
a) Lien du projet Github: https://github.com/Pauline1997fabiola/TPnot-_Fabiola.git
