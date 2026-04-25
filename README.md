# Atelier 2 - Django Ecommerce

## Description
Application web ecommerce développée avec Django et MySQL, conteneurisée avec Docker.

## Technologies utilisées
- Python 3.13
- Django
- MySQL 8.0
- Docker & Docker Compose

## Prérequis
- Python 3.13+
- Docker Desktop
- Git

## Installation

### 1. Cloner le projet
```bash
git clone https://github.com/khaoula3801/atelier2-Django.git
cd atelier2-Django
```

### 2. Créer et activer l'environnement virtuel
```bash
python -m venv myenv
.\myenv\Scripts\Activate.ps1
```

### 3. Installer les dépendances
```bash
pip install -r requirements.txt
```

### 4. Lancer la base de données MySQL avec Docker
```bash
docker-compose up -d
```

### 5. Appliquer les migrations
```bash
python manage.py migrate
```

### 6. Lancer le serveur
```bash
python manage.py runserver
```

### 7. Accéder à l'application
Ouvrez votre navigateur sur :