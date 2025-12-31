# shrine_car_shows
This will be the repository for the cross platform (iOS and Android) apps for the Shriner Car Shows

carshow_api/
│
├── main.py
│
├── app/
│   ├── __init__.py
│   │
│   ├── database/
│   │   ├── __init__.py
│   │   ├── connection.py
│   │
│   ├── models/
│   │   ├── __init__.py
│   │   ├── owners.py
│   │   ├── vehicles.py
│   │   ├── registrations.py
│   │   ├── judges.py
│   │   ├── scores.py
│   │   ├── shows.py
│   │   ├── classes.py
│   │
│   ├── schemas/
│   │   ├── __init__.py
│   │   ├── owners.py
│   │   ├── vehicles.py
│   │   ├── registrations.py
│   │   ├── judges.py
│   │   ├── scores.py
│   │   ├── shows.py
│   │   ├── classes.py
│   │
│   ├── routers/
│   │   ├── __init__.py
│   │   ├── owners.py
│   │   ├── vehicles.py
│   │   ├── registrations.py
│   │   ├── judges.py
│   │   ├── scores.py
│   │   ├── dashboard.py
│   │
│   ├── services/
│   │   ├── __init__.py
│   │   ├── qr_service.py
│   │   ├── registration_service.py
│   │   ├── scoring_service.py
│   │
│   ├── utils/
│       ├── __init__.py
│       ├── validators.py
│       ├── helpers.py
