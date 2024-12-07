# Multi_Agent_Application

## Description
**Multi_Agent_Application** est une application avancée basée sur l'IA conçue pour exploiter plusieurs grands modèles de langage (**LLMs**) afin d'effectuer des tâches spécifiques. Cette application utilise des outils de pointe comme **Python**, **Langflow**, **Astra DB** et **Streamlit** pour acheminer dynamiquement les tâches entre les modèles et fournit une interface utilisateur interactive permettant d’interagir avec l’application.

## Fonctionnalités
- Système multi-agent utilisant plusieurs LLMs.
- Routage dynamique des tâches vers l'agent le plus adapté.
- Interface utilisateur interactive construite avec Streamlit.
- Intégration fluide avec Astra DB pour le stockage des données.
- Architecture facilement extensible pour ajouter d'autres agents ou fonctionnalités.

## Outils et technologies
- **Python** : Langage de programmation principal.
- **Langflow** : Pour concevoir les workflows d'IA.
- **Astra DB** : Base de données NoSQL gérée.
- **Streamlit** : Framework pour créer l'interface utilisateur.
- **OpenAI API** : Pour accéder aux LLMs.

### Variables d'environnement
Créez un fichier `.env` dans le répertoire racine avec les clés suivantes :
```env
OPENAI_API_KEY="votre_cle_api_openai"
ASTRA_DB_APPLICATION_TOKEN="votre_token_application_astra_db"
LANGFLOW_TOKEN="votre_token_langflow"
ASTRA_ENDPOINT="votre_url_endpoint_astra"
