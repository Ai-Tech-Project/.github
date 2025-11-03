# Projet Ai-Tech

Bienvenue sur le projet Ai-Tech, une application web complète développée avec une architecture moderne et évolutive.

## 🚀 Aperçu du Projet

Ai-Tech est une plateforme qui combine une interface utilisateur moderne (Angular) avec des API performantes (FastAPI et Spring) pour offrir une expérience utilisateur fluide et réactive.



## 🏗️ Architecture

Le projet est structuré en trois composants principaux :

1. **Frontend (AiTech-Angular)**
   - Développé avec Angular 17
   - Interface utilisateur moderne et réactive
   - Communication avec les APIs backend

2. **Backend API 1 (AiTech-FastAPI)**
   - Développé avec Python FastAPI
   - API RESTful performante
   - Documentation Swagger intégrée

3. **Backend API 2 (AiTech-Spring)**
   - Développé avec Java Spring Boot
   - Microservices complémentaires
   - Intégration avec des services avancés

## 🛠️ Prérequis

- Node.js et npm (pour le frontend Angular)
- Python 3.7+ (pour FastAPI)
- Java 11+ (pour Spring Boot)
- Git

## 🚀 Installation et Configuration

### Frontend (Angular)

```bash
cd AiTech-Angular
npm install
ng serve
```

### Backend FastAPI

```bash
cd AiTech-FastApi
python -m venv venv
source venv/bin/activate  # Sur Windows: .\venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### Backend Spring

```bash
cd AiTech-Spring
./mvnw spring-boot:run
```

## 🌐 Accès aux applications

- **Frontend**: http://localhost:4200
- **FastAPI**: http://localhost:8000
- **Spring Boot**: http://localhost:8080
- **Documentation FastAPI**: http://localhost:8000/docs
- **Documentation Spring Boot**: http://localhost:8080/swagger-ui.html

## 📂 Structure des Dossiers

```
Ai-Tech-Project/
├── .github/             # Fichiers de configuration GitHub
├── AiTech-Angular/      # Application frontend Angular
├── AiTech-FastApi/      # API FastAPI
└── AiTech-Spring/       # API Spring Boot
```

## 🤝 Contribution

1. Forkez le projet
2. Créez votre branche (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Poussez vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📝 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

Développé avec ❤️ par l'équipe Ai-Tech
