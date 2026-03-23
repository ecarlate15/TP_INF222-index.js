# TP_INF222-blog-api.git
API backend pour gérer un blog simple

# Blog API

## Installation
npm install
node app.js

## Endpoints

POST /api/articles  
GET /api/articles  
GET /api/articles/:id  
PUT /api/articles/:id  
DELETE /api/articles/:id  
GET /api/articles/search?query=texte  

## Exemple JSON

{
  "titre": "Mon article",
  "contenu": "Contenu ici",
  "auteur": "John",
  "date": "2026-03-23",
  "categorie": "Tech",
  "tags": "Node.js,API"
}
