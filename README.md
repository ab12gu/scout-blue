# FRC Scouting Application

Scouting app for frc

Domain Address: [https://scout.blue](https://scout.blue)

# Installation

1. Clone the repo locally:

```
git clone https://github.com/ab12gu/frc-scouting-app
cd frc-scouting-app
```

2. Install project dependencies
```
pip install -r requirements.txt
```

# Deploy

Local deploy, run:
```
python manage.py runserver
```

Ensure you are keeping the requirements.txt most up-to-date:
```
pip freeze > requirements.txt
```

# Architecture

Languages:
- Frontend: `HTML/CSS`
- Backend: `Python`
- DB: `SQL`

Libraries/structure: 
- Web Framework: `Django`
- Backend DB: `Postgresql`

Hosting websites
- Hosting Platform: `Render`
- DB Host: `Subabase`