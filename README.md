Site et Blog
git clone 
python3.9 -m venv .env # creation de l'environnemrnt virtuel
source .env/bin/activate # activation de l'environnemrnt virtuel
which python # verifier la version de python
pip install --upgrade pip # mettre a joiur pip
python -m django --version # verifier la version de django
pip install django==3.1.7 # installer django
pip freeze > requirements.txt # creer le fichier requirements
pip install -r requirements.txt # insttaller requirements pour les bibliotheques 

django-admin startproject nom_du_projet # CRÉER UN NOUVEAU PROJET
python manage.py startapp nom_de_l’app # CRÉER UNE APPLICATION