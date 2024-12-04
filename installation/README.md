# Installation d'un Environnement Virtuel et des Dépendances en Local

### Créer un environnement virtuel
```bash
python -m venv env
```
```bash
source env/bin/activate
```
```bash
pip install --upgrade pip
```
```bash
pip install notebook
```
```bash
pip install pyspark pandas
```

### Lancer la base de données mysql :
```bash
docker compose up
```

localhost:8080 
root/root