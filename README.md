# Microblog
Blog app based on Miguel Grinberg's [Flask Mega Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)

### Languages
The app can be used in English and Spanish. Change your browser language settings or choose the right return xx line in app/config.py. Translations are in .po files and Python produces .mo files.

Update your translations with these 3 commands:
1. pybabel extract -F babel.cfg -k _l -o messages.pot .
2. pybabel update -i messages.pot -d app/translations
3. pybabel compile -d app/translations

### Installing requirements
pip install -r requirements.txt

### Database update
1. flask db migrate -m "description of the change made"
2. flask db upgrade
