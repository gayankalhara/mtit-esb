# Scenario

The scenario represents a simple email checking application using the Gmail REST API v1.0 available
in OAuth Playground. It demonstrates sample requests for,

  - Display user’s profile (Type : GET)
  - Display list of user’s emails (Type : GET)
  - Display a selected email from the list (Type : GET)
  - Display list of draft emails (Type : GET)
  - Display list of threads (Type : GET)
  - Move a selected thread to Trash folder (Type : POST)

# Authentication & API Access

Gmail REST API uses OAuth 2.0 Authentication method. Authentication is carried out using a temporary Authentication Token, which should be sent as a header (Authentication) with each request to the API. New token should be obtained once the current Token expires.

Example Authentication Token:
```json
"Bearer ya29.GlteBB5b-hu8eCcVB2OrmEnT5KMOuappGdG5syqDMK6VdAYt1kzSZPrIlw7DVEgkp8OWGx7NRdRu2fWZ_
EGfkd2gv2vbwof1uaJM3EGOC7s7BHy65kcgPw4Z7G8"
```
