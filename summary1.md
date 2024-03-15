fetch('https://restcountries.com/v3.1/name/ca')
            .then((response) => response.json())
            .then((data) => console.log(data))
            .catch((error) => console.log(error));
			

Appels API (fetch ou axios): 

# 1 - Le navigateur 
# 2 - POSTMAN
# 3 - curl
# 4 - Swagger
# 5 - Ajout de plugins dans VSCODE REST CLIENT
# 6 - Javascript sur le navigateur 
# 7 - Application cliente avec un fichier js 


Détails : 

# 1 - Le navigateur (URL) : https://restcountries.com/v3.1/name/ca (Uniquement GET)
# 2 - POSTMAN : nouveau http + GET + Coller l'URL (GET, POST, PUT, DELETE + supporter parametres et corps)
# 3 - curl https://restcountries.com/v3.1/name/ca
# 4 - Swagger (ajout du code)
# 5 - Ajout de plugins dans VSCODE REST CLIENT
# 6 - Via le navigateur (Inspecter + + console + js) 
# 7 - Application cliente avec un fichier js  (par exemple REACT - application Drapeau ou js)



Dans notre application drapeau, nous avons utilisé deux apples API 
# 1 - Composant Recherche : https://restcountries.com/v3.1/name/{name}
# 2 - Composant pays : https://restcountries.com/v3.1/alpha/{code}

# Exemple Curl sur Windows


mvn spring-boot:run

curl -X POST http://localhost:8080/clients -H "Content-Type:application/json" -d "{\"name\": \"Haythem REHOUMA\", \"email\": \"hrehouma@baeldung.com\"}"
{"id":3,"name":"Haythem REHOUMA","email":"hrehouma@baeldung.com"}


http://localhost:8080/clients

https://www.baeldung.com/spring-boot-react-crud
