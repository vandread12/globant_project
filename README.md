# Globant project

\# Project structure

globant-data-migration/

├── README.md

├── Dockerfile

├── docker-compose.yml

├── requirements.txt

├── src/

│   ├── \_\_init\_\_.py

│   ├── config.py

│   ├── database/

│   │   ├── \_\_init\_\_.py

│   │   ├── models.py

│   │   └── db\_manager.py

│   ├── api/

│   │   ├── \_\_init\_\_.py

│   │   ├── app.py

│   │   ├── routes.py

│   │   └── validators.py

│   ├── migration/

│   │   ├── \_\_init\_\_.py

│   │   └── csv\_loader.py

│   ├── backup/

│   │   ├── \_\_init\_\_.py

│   │   ├── avro\_backup.py

│   │   └── restore.py

│   └── utils/

│       ├── \_\_init\_\_.py

│       └── logger.py

├── tests/

│   ├── \_\_init\_\_.py

│   ├── test\_api.py

│   ├── test\_migration.py

│   └── test\_backup.py

└── data/

├── csv/

│   ├── departments.csv

│   ├── jobs.csv

│   └── hired\_employees.csv

└── backup/

└── # Backup files will be stored here
