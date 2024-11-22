tp 2

1- 
Sur postman : 
copie de ce lien dans une nouvelles requête https://jsonplaceholder.typicode.com/comments selectionné "GET" puis cliqué sur "SEND"

[
    {
        "postId": 1,
        "id": 1,
        "name": "id labore ex et quam laborum",
        "email": "Eliseo@gardner.biz",
        "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
    },
2- 

Modifié l'url https://jsonplaceholder.typicode.com/comments par https://jsonplaceholder.typicode.com/todos selectionné "POST" puis cliqué sur "SEND" puis dans body selectionné x-www-form-urlencoded et y ajouter les valeurs dans key et values 
resultat 

{
    "Userid": "1",
    "id": 201
}

3- 

Reprendre l'url et la modifier de la sorte https://jsonplaceholder.typicode.com/posts/1/ selectionné "PATCH" puis "SEND" puis aller dans raw puis json et ecrire ceci { "title": "Updated Title", "body": "Updated body." }

resultat
{
  "userId": 1,
  "id": 1,
  "title": "Updated Title",
  "body": "This is the updated body text."
}

-4

Utiliser ce lien  https://jsonplaceholder.typicode.com/posts/1/comments puis selectionné "GET" puis "SEND" 

resultat

[
  {
    "postId": 1,
    "id": 1,
    "name": "id labore ex et quam laborum",
    "email": "Eliseo@gardner.biz",
    "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
  },


5-

Utiliser le lien https://jsonplaceholder.typicode.com/albums/2/photos "GET" puis "SEND"

resultat 

[
  {
    "albumId": 2,
    "id": 51,
    "title": "non sunt voluptatem placeat consequuntur rem incidunt",
    "url": "https://via.placeholder.com/600/8e973b",
    "thumbnailUrl": "https://via.placeholder.com/150/8e973b"
  },
